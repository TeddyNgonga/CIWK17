pipeline {
	agent any

		
	stages {
	
	
		stage('Maven: clean project') {
				steps {
									bat """ cd "C:\\Users\\212614467\\eclipse-workspace\\HelloMaven"
									
									mvn install
									
					"""
				}
		}
			stage('Maven: package project') {
					steps {
									bat """
									
									mvn package
									
					"""
					}
		}
			stage('Maven: test project'){
				steps{
									bat """
									
									mvn test
									
				"""
				}
		}
		
	}
}
