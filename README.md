# Ivo1
Basic Class Stuff



pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build') {
            steps {
                echo 'Welcome World'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Happy World'
            }
        }
        stage('Test') {
            steps {
                echo 'Great World'
            }
        }
        stage('Release') {
            steps {
                echo 'Best World'
            }
        }
        
        
    }
}
