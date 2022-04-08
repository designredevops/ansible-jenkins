pipeline {
    agent {label "embedded"}
    stages {
        stage('Ansible Task') {
            steps {
              sh 'ansible-playbook playbook.yml'
            }
        }
    }
}