pipeline {
    parameters {
    string(name: 'BRANCH', defaultValue: 'master', description: 'Branch to Build')
    }
    agent { dockerfile true }

    stages {
        stage('Test') {
            steps {
                echo "Test"
            }
        }
    }
}