pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
                sh 'cd frontend'
                sh 'npm start'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}