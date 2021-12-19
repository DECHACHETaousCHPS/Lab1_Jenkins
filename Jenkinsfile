pipeline {
     agent any
     stages{
        stage('build'){
            steps{
                sh "cd webapp"
                sh "mvn clean "
                sh "mvn clean install"

             }
        }
   
	stage('Test') {
            steps {
                sh 'cd ../target/' 
                j 
            }
        }  
  
     

      

    }

 }

