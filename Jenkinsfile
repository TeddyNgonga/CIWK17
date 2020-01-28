pipeline {
	agent any
		tools {
			maven 'maven'
		}
		
	stages {
	
	
		stage('Maven: clean project') {
				steps {
									bat """
									
									mvn clean
									
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
