pipeline {	
    agent any	
    options {	
		timestamps()
		overrideIndexTriggers(true)
	        //overrideIndexTriggers(env.BRANCH_NAME == 'thang')
    }
    stages {	
        stage('Build') {	
            steps {
                echo 'Hello World 1'
		echo env.BRANCH_NAME
            }	
        }	
    }	
}	
