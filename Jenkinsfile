pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                def stdout = powershell(returnStdout: true, script: '''
                echo 'NAVEEN KUMAR'
    ''')
    println stdout
                }
            }
        }
    }
