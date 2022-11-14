pipeline {
    agent any

    stages {
        stage ('Clean Stage') {

            steps {
                
                    sh 'mvn clean'
                
            }
        }

        stage ('Testing Stage') {

            steps {
               
                    sh 'mvn test'
                
            }
        }


        stage ('Package Stage') {
            steps {
                
                    sh 'mvn package'
                
            }
        }
    }
}
