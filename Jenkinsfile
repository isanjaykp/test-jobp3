pipeline {
    agent win-agent1
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
