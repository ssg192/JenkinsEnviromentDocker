pipeline {
    agent any
    tools{
        maven 'M3_9_9'
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
