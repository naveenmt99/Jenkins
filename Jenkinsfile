pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                   powershell returnStatus: true, script: '.\\build.ps1'
                    }
                }
            }
        }
    }
