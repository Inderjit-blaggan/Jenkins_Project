pipeline {
    agent any
    
    stages{
        
        stage('build')
        {
            steps{
                    echo 'building the application'
            }
            
        }
        stage('artifact')
        {
            steps{
                    echo 'Artifacting the application'
            }
            
        }
    
    
    }
    post{
        always{
            echo " this is executed every time"
        }
        success{
            echo " Congratulations build is successful"
        }    
        failure{
            echo "Please check the logs build encounted a failure"
        }
    
    }    
        

}
