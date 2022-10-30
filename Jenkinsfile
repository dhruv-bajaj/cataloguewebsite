pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
               bat  'cd frontend/frontend'
               bat 'npm i'
               bat 'npm start'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}