pipeline {
     agent any
     stages{
        stage('build'){
            steps{
                sh "mvn clean "
                sh "mvn clean install"

             }
        }
   
	stage('Test') {
            steps {
                sh 'make check || true' 
                junit '**/target/*.war' 
            }
        }  
  
     

      

    }

 }

