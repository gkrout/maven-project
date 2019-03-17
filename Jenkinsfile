pipeline {
	agent any
  stages {
		stage('One') {
			steps {
				sh 'mvn clean'
			}
		}
		stage('Two') {
			steps {
				sh 'mvn test'
			}
		}
		stage('Three') {
			steps {
				sh 'mvn package'
			}
		}
	}
}
