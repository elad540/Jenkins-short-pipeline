pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git "https://github.com/elad540/newripo.git"
                sh 'ls -ltr'
            }
        }
    }
}
