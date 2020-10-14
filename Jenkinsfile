pipeline {
    agent any
    stages {
        stage('Sonar Analysis') { 
            steps {
                withSonarQubeEnv('sonar') {
                 sh 'mvn clean package sonar:sonar'
              }
            }
        }
    }
}
