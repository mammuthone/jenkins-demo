pipeline {
    agent any 
    stages {
        stage('Clonare il repository') {
            steps {
                git branch: 'main', url: 'https://github.com/mammuthone/jenkins-demo'
            }
        }
    }
}