pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/username/repository.git'
            }
        }
        stage('Display README') {
            steps {
                sh 'cat README.md'
            }
        }
    }
}
