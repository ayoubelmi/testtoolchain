pipeline {
    agent { dockerfile { 
                  filename 'Dockerfile'
                  label 'docker-agent' } 
          }
    stages {
        stage('Test') {
            steps {
                sh './gradlew build'
            }
        }
    }
}
