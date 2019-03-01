pipeline{
    agent none

    environment{
        PROJECT_NAME="ActivityService" 
        BUILD_FILE_NAME="${PROJECT_NAME}_${BUILD_NUMBER}.tar.gz"              
    }

    stages{
        stage('SonarQube analysis'){            
            steps{               
                    sh "pwd"
                    
            }                  
        }                     
    }
}
