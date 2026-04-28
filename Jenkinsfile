pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/vishwachandra2710/node-js-sample.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Run App') {
            steps {
                bat 'node index.js'
            }
        }
    }
}