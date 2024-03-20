pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh './gradlew init'
                sh 'sudo ./gradlew build'
            }
        }
    }
}
