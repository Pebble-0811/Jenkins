pipeline {
    agent any

    tools {
        maven 'maven0811'
    }

    stages {
        stage('Build') {
            steps {
                bat 'mvn -version'
            }
        }
    }
}
