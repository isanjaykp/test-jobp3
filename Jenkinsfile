pipeline {
    agent any
    stages {
        stage('check mvn version push') {
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
