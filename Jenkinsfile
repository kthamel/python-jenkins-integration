pipeline {
    agent any

    stages {
        stage('Check_binaries') {
            steps {
                sh "python3 --version"
            }
        }

        stage('Execute_progrm') {
            steps {
                sh "python3 test.py"
            }
        }
    }
}