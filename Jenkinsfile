pipeline {
	agent none
	stages {
		stage('Build Image') {
			agent any
			steps {
				sh 'docker build -t saikumar2305/helloworld:${BUILD_NUMBER} .'
				sh 'docker tag saikumar2305/helloworld:${BUILD_NUMBER} saikumar2305/helloworld:latest'
			}
		}
	}
}
