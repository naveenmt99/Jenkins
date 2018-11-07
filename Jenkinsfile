pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                files = findFiles(glob: '*.*')
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
