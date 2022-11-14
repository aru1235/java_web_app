pipeline {
    agent any
    environmental {
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
    }
}
