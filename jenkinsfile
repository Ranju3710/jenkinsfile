pipeline {
  agent any			
  stages {
         stage ('Build') {	
	     steps {
                   echo "Hello, Pipeline! Build this job"
		}
          }
          stage ('Test') {
		steps {
                      echo "Test this project"
		} 
          }
          stage ('Deploy') {
		steps {
                      echo "Deploy in Production"              
		}
         }
  }
}
