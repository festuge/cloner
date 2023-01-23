pipeline {
    agent any
      stages{
        stage('clone-repo'){
            steps{
                git branch: 'main', credentialsId: 'github-id', url: 'https://github.com/festuge/cloner.git'
            }
        }
      }
}