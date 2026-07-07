pipeline {
    agent any
    
    stages {
        stage ('clone the repository ') {
            steps {
                git branch: 'patch-2', url: 'https://github.com/gani3733/user-registration.git'
            }
        }
        
        stage('Build the application ') {
            steps {
                sh 'mvn clean package'
            }
        }
        
    }
}
