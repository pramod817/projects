pipeline {
    agent any
    stages {
        stage('Sonar Analysis') { 
            steps {
                withSonarQubeEnv('sonar') {
                 sh 'mvn sonar:sonar'
              }
            }
        }
    }
}
