pipeline {	
    agent any	
    options {	
		timestamps()
		overrideIndexTriggers(false)
	        overrideIndexTriggers(env.BRANCH_NAME == 'thang')
    }
    stages {	
        stage('Build') {	
            steps {
                echo 'Hello World 4-1'
		echo env.BRANCH_NAME
            }	
        }	
    }	
}	
