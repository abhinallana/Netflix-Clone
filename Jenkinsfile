pipeline{
    agent any

    stages{
        stage('Git Checkout'){
            steps{
            git 'https://github.com/abhinallana/Netflix-Clone.git'
        }
        }
        stage('Build Docker Image'){
            steps{
                sh 'docker --version'
                sh 'docker build . -t abhinallana/netflixclone'
            }
            

        }
    }
    
}