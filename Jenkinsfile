pipeline {
    agent any

    stages {
        stage('Check_dependencies') {
            steps {
                echo 'python3 --version'
            }
        }


        stage('Execute_progrm') {
            steps {
                python3 test.py
            }
        }
    }
}