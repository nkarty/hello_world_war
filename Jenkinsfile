pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/nkarty/hello_world_war.git'
            }
        }
        
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t check_img1 .'
            }
        }
    }
}
