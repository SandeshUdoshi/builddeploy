pipeline {
    agent any
    tools {
    maven 'mavencfg'
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
