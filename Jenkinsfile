pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
               sh 'mvn clean package deploy:deploy'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
