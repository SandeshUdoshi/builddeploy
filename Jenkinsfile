pipeline {
    agent any
    tools {
    maven '3.8.6'
    }

    stages {
        stage ('Compile Stage') {

            steps {
                
                    sh 'mvn compile'
                
            }
        }

        stage ('Package Stage') {

            steps {
                
                    sh 'mvn package'
                
            }
        }


        
    }
}
