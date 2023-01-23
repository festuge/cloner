pipeline {
    agent any
      stages{
        stage('clone-repo'){
            steps{
                git branch: 'main', credentialsId: 'github-id', url: 'https://github.com/festuge/cloner.git'
            }
        }
        stage('system-check'){
            steps{
                sh 'bash -x lscpu'
            }
        }
      }
}