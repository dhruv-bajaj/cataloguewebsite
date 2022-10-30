pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
              bat '''cd frontend
                    npm i
                    npm start'''
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}