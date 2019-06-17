pipeline {
    agent { dockerfile { 
                  filename 'Dockerfile'
                  label 'android' } 
          }
    stages {
        stage('Test') {
            steps {
                sh './gradlew build'
            }
        }
    }
}
