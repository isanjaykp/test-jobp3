pipeline {
    agent any
    stages {
        stage('check mvn version') {
            steps {
                sh 'mvn --version'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean compile'
            }
        }
    }
}
