pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main', credentialsId: 'github-token', url: 'https://github.com/versatile-life/jenkins-demo.git'
            }
        }
        stage('Build') {
            steps {
                echo '✅ Build stage: Simulating build...'
            }
        }
        stage('Test') {
            steps {
                echo '🧪 Test stage: Simulating tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo '🚀 Deploy stage: Simulating deploy...'
            }
        }
    }
}
