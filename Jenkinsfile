pipeline {

agent any

stages {
	stage('SCM') {
		steps {
			echo "git pull mycode step1"
			echo "git pull mycode step2"
		}
	}
		
	stage('Deploy') {
		steps {
			echo "deploying my code"
		}
	}
	
	stage('Test') {
		steps {
			echo "testing my code"
		}
	}
	
	stage('Prod') {
		steps {
			echo "Production code"
		}
	}

	}
}