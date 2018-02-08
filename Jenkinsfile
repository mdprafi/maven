pipeline {
	agent any
 
	tools {
		maven 'maven_3_5_0'
		jdk 'Jdk1.8'
	}
	
    stages {
               stage('Initialize') {
                 steps {
		    
	            echo "PATH = %PATH%"
		    echo "M2_HOME = %M2_HOME%"
		   
		     }
            }
	    
	    
	    stage('Build') {
                 steps {
			 bat 'mvn install'
		       }
                }
	    
        }
        
    }
