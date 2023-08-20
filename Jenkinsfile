pipeline {
    agent any
    stages {
        stage('check mvn version push') {
            steps {
                bat 'mvn --version'
            }
        }
        stage('Build') {
            steps {
                bat 'mvn -B -DskipTests clean compile'
            }
        }
    }
}
