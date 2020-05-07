pipeline {
    agent 8888

    stages {
        stage ('Compile Stage') {

            steps {
                
                    sh 'mvn clean compile'
                
            }
        }

        stage ('Testing Stage') {

            steps {
                
                    sh 'mvn test'
                
            }
        }


        stage ('Deployment Stage') {
            steps {
             
                    sh 'mvn --version'
             
            }
        }
    }
}
