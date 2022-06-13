pipeline {
    agent any 
    options {
        timestamps()
        timeout(time: 1, unit: 'HOURS')
    }
	environment {
        IsTest = "${params.IsTest}"			
	}
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
                echo IsTest
            }
        }
    }
}