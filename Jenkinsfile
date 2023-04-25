pipeline {  
    agent any  
    stages  {  
            stage ('Build') {  
                 steps {  
                        echo 'Building...'  
                        sleep 5
                }  
            }  
            stage ('Test') {  
steps {  
                        echo 'Testing...'  
          sleep 5
                }   
            }  
            stage ('QA') {  
steps {  
                        echo 'QA...'  
          sleep 5
                }  
            }  
            stage ('Deploy') {  
    steps {  
                        echo 'Deploying...'  
          sleep 5
                }  
            }  
            stage ('Monitor') {  
    steps {  
                        echo 'Monitoring...'  
          sleep 5
                }  
            }  
    } 
    post {  
        always {
            echo 'Execute Always'
        }
       success {
            echo 'Success'
        }
        failure {
            echo 'Failure'
        }
    }
}
