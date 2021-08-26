pipeline { 
    agent 'maven'  
    stages { 
        stage('Test') { 
            steps { 
               sh './mvnw verify'
            }
        }
    }
}
