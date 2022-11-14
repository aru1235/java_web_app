pipeline {
    agent any
    environment {
        PATH = "/opt/maven/bin:$PATH"
    }

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
        
        stage ('printing') {
            steps {
                sh echo "building is done"
            }
        }
    }
}
