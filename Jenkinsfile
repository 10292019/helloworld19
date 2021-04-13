pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
              stage('build') {
            steps {
                echo 'Hello build'
                sleep 10
            }
        }
              stage('test') {
            steps {
                echo 'Hello test'
                sleep 5
            }
        }
              stage('deploy') {
            steps {
                echo 'Hello deploy'
                pwd
            }
        }
        stage('push') {
            steps {
                echo 'Hello push'
                sh 'docker ps'
            }
        } 
    }
}
