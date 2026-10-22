pipeline {
    agent any
    tools {
        maven 'Maven 3.10.0'
    }   
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
     }
}
