pipeline {
    agent any

    stages {
      stage("Prep") {
       steps{
        //deleteDir() // Clean up the workspace
       // checkout scm
        withCredentials([file(credentialsId: 'secret', variable: 'secret')]) {
            bat 'echo  %secret%'
        }
          }
    }  
            
        stage('Build') {
            steps {
                script {
                   bat 'echo %PATH%'
                    }
                }
            }
        }
    }
