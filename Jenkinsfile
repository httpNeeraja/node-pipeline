pipeline {
    agent any

    tools {
        nodejs 'NodeJS' 
    }

    stages {
        stage('Run') {
            steps {
                sh 'npm start'
            }
        }

        
    }

    post {
        always {
            cleanWs()
        }
    }
}