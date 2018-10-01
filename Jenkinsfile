pipleline{
	environment {
		registry = “saikumar2305/helloworld”
		registryCredential = ‘dockerhub’
	}
	agent none
	stages {
		stage(‘Docker Build’) {
			steps {
				sh ‘docker build -t saikumar2305/helloworld:${BUILD_NUMBER} .’
				sh ‘docker tag saikumar2305/helloworld:${BUILD_NUMBER} saikumar2305/helloworld:latest’
			}
		}
	}
}
