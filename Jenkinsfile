pipeline {
    agent any
    stages {
        stage('Sonar Analysis') { 
            steps {
                withSonarQubeEnv('SonarQube') {
                 sh 'mvn sonar:sonar'
              }
            }
        }
    }
}
