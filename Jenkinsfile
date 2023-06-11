pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'chmod a+x gradlew && ./gradlew -version'
            }
        }
    }
}