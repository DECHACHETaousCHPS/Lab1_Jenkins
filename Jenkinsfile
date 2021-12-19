pipeline {
     agent any
     stages{
        stage('build'){
            steps{
                sh "cd webapp"
                sh "mvn clean "
                sh "mvn package"

             }
        }
   
	stage('Test') {
          steps{}
                
              
        }  
  
     

      

    }

 }

