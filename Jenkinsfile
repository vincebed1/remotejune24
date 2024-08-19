pipeline {
	agent any
	stages {
		stage('Hello') {
			steps{
				echo "Hello, welcome to the demo branch in Jenkins"
			}
		}
		stage('Print demo.txt') {
			when {
				branch "demo*"
			}
			steps{
				sh 'cat demo.txt'
			}
		}
	}
}
