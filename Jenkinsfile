pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/sazid7070/ansible-cicd-demo.git'
            }
        }

        stage('Run Ansible') {
            steps {
                sh 'ansible-playbook install_nginx.yml'
            }
        }
    }
}
