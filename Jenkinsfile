pipeline {
    agent any
    stages {
        stage('Sonar Analysis') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
