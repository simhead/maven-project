pipeline {
    agent any
    stages{
        stage('Build'){
            steps {
                echo 'Hello from pipeline script!!!'
            }
            post {
                success {
                    echo 'Now in post flow...'
                }
            }
        }
    }
}
