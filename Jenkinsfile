pipeline {
    agent any
    tools {
         maven 'M2_HOME'
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello build'
                
            }
        }
              stage('build') {
            steps {
                sh 'mvn clean'
                sh 'mvn install'
                sh 'mvn package'
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
                sh 'pwd'
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
