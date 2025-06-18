pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
git branch: 'main', url: 'https://github.com/Tarek-Sayed169/Jenkins-test.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
