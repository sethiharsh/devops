pipeline{
    agent any
    environment{
        PROJECT_NAME="ActivityService" 
        BUILD_FILE_NAME="${PROJECT_NAME}_${BUILD_NUMBER}.tar.gz"              
    }
    stages{
        stage('Build code'){
        //agent { label 'master' }              
            steps{               
                  sh "pwd"   
            }                  
        }                     
    }
}
