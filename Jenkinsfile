pipeline {
    agent any
    stages {
        stage("ansible") {
            steps {
                ansiblePlaybook(playbook: 'project.yml', inventory: 'hosts')
            }          
        }        
    }
}
