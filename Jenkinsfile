pipeline {
    agent any

    stages {
        stage('Who Am I') {
            steps {
                sh '''
                  echo "Running on node:"
                  hostname
                  whoami
                '''
            }
        }

        stage('Run Telecom App') {
            steps {
                sh './app.sh'
            }
        }
    }
}

