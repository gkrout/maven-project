pipeline {
	agent any
	tools {
		maven 'maven3.6.0'
		jdk 'java'
	}
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
