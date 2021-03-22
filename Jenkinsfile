@Library('local-shared-library@master') _
loadLocalLibrary scm, "library"

pipeline {
	agent any
	stages {
		stage("Test") {
			steps {
				sh '''echo "hello" '''
				localTest()
			}
		}
	}
}
