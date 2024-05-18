pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'git@github.com:Niemetz/JTE.git'
            }
        }
        stage('Display README') {
            steps {
                sh 'cat README.md'
            }
        }
    }
}
