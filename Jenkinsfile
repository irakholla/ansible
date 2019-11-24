pipeline {
    agent any
    stages {
        stage("ansible") {
            steps {
                ansiblePlaybook(playbook: 'playbook.yml', inventory: 'hosts')
            }          
        }        
    }
}
