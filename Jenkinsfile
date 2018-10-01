pipeline {
	agent none
	stages {
		stage('Build Image') {
			agent any
			steps {
				sh 'docker build -t saikumar2305/helloworld:latest'
			}
		}
	}
}
