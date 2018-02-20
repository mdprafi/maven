pipeline {
	agent any
 
	
	
    stages {
	         stage ('Cleaning stage') {
		    steps {
		    bat 'mvn clean'
		     }
	          }
	    
	         stage ('Compile stage') {
		    steps {
		    bat 'mvn compile'
		    }
	          }
	    
	        stage('Build') {
                 steps {
			 bat 'mvn instal'
		       }
                }
	    
        }
        
    }

