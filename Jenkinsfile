pipeline {
    agent any

    stages {
        stage('Run Ansible') {
            steps {
                sh 'ansible-playbook install_nginx.yml'
            }
        }
    }
}
