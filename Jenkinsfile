pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat '"C:\\Users\\ankit_frj21mc\\AppData\\Local\\Programs\\Python\\Python312\\python.exe" -m pip install pytest'
            }
        }

        stage('Test') {
            steps {
                bat '"C:\\Users\\ankit_frj21mc\\AppData\\Local\\Programs\\Python\\Python312\\python.exe" -m pytest'
            }
        }
    }
}