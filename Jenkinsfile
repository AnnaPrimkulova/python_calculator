pipeline {
	agent any
	stages {
		stage("Run the code!") {
			steps {
				sh """
					python calculator.py
				"""
			} //steps
		} //stage
		stage("Run unit test") {
			steps {
				sh """
				 pytest
				 """
			} //steps
		} //stages
	} //stages
} //pipeline
