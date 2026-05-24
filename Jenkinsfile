pipeline {
    agent any

    environment {
        ENV = "prod"
        APP_NAME = "my-app"
    }

    stages {

        stage('Build') {
            steps {
                echo "Building ${APP_NAME}"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying to ${ENV} environment"
            }
        }
    }
}
