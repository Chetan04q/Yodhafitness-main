pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/Chetan04q/Yodhafitness-main.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the gym website...'
                // Example: copy files to a folder or run a simple local test
                sh 'echo "Website deployed successfully!"'
            }
        }
    }
}