pipeline {
    agent any
    
    stages{
        stage('SCM'){
            steps{
                echo "This is SCM"
                sh "date"
                git branch: 'main', url: 'https://github.com/anandwork75/webcontainer.git'
            }
        }
        stage('Build'){
            steps{
                echo "This is Build"
                sh 'date'
            }
        }
        stage("Test"){
            steps{
                echo "This is Test"
            }
        }
        stage("Deploy"){
            steps{
                echo "This is Deploy"
            }
        }
    }
    
}
