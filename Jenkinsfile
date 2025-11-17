pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Kartikk525215/Agency_Proj.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building Portfolio Website…"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy step will go here…"
            }
        }
    }
}
