pipeline {	
    agent any	
    options {	
		timestamps()
		overrideIndexTriggers(false)
	        //overrideIndexTriggers(env.BRANCH_NAME == 'thang')
    }
    stages {	
        stage('Build') {	
            steps {
                echo 'Hello World 3'
		echo env.BRANCH_NAME
            }	
        }	
    }	
}	
