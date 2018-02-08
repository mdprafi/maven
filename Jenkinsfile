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
		    bat 'mvn comppile'
		    }
	          }
	    
	        stage('Build') {
                 steps {
			 bat 'mvn install'
		       }
                }
	    
        }
        
    }
