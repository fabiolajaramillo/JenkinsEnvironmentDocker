
pipeline {
    agent any
    tools {
        maven 'M3_8_6'
    }
    stages {
        stage('Build') {
            steps {
                dir("Curso-Microservicios/"){
                    sh "mvn clean package"
                }
            }
        }
    }
}