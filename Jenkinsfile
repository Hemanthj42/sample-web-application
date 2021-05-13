pipeline{
 
    agent any
    
    environment{
         PATH = "/opt/maven-3.3.9/bin:$PATH"
         
     }
  
        stages{
           stage('build'){
               steps{
		sh "mvn clean install"
	       }
	   }
		
    }    
