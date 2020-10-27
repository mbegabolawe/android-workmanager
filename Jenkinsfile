pipeline {
    agent {dockerfile true}
    environment {
        appName = 'Android-Work-Manager'
    }
    stages {
        stage("Build") {
            steps {
                sh './gradlew assemble'
            }
        }
    }
}