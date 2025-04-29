pipeline {
    agent any  // This tells Jenkins to run on any available agent

    stages {
        stage('Build') {
            steps {
                echo '🏗️  Building the project...'
                sh 'echo Compiling code...'
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Running tests...'
                sh 'echo All tests passed!'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying the application...'
                sh 'echo Application deployed!'
            }
        }
    }
}
