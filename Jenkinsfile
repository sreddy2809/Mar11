pipeline{
	agent any
	stages{
		stage("One"){
		  options {
          timestamps()		  
		  retry(3) 
		  }
			steps{
			   echo " Testing"
			   sh """
			      pwd
				  ls -l 
				  
			   """
			}
			
		}
	}
}
