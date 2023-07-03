pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps {
          sh 'echo "1234" | sudo -S apt-get install npm'
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
