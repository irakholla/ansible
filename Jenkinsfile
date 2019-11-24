pipeline {
    agent any
    stages {
        stage("ansible") {
            steps {
                ansiblePlaybook(playbook: 'plroject.yml', inventory: 'hosts')
            }          
        }        
    }
}
