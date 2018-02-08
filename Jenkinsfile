pipeline {
	agent {
		label "windows"
	}
 
	tools {
		maven 'maven_3_5_0'
		jdk 'java8'
	}
	
    stages {
               stage('Compile Stage') {
                 steps {
		    bat ...
	            echo "PATH = C:\Maven\apache-maven-3.5.0\bin"
		    echo "M2_HOME = C:\Maven\apache-maven-3.5.0"
		    ...
		     }
            }
        }
        
    }
