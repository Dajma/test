pipeline {
    agent any

    stages {

        stage("build") {

            steps {
                sh 'echo building the application '
            }
        }

        stage("test") {

            steps {
               sh 'echo tesing the application '
               sh 'echo mesting tesing the application '
               sh 'docker run localhost:5000/nginx-alpine ifconfig'
            

            }    
        }

    }
}