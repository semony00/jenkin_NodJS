pipeline {
	agent any
	tools {nodejs "myNode"}
	stages{
		stage("check version"){
			steps{
				echo "checking version"
				sh "node --version"
			}
		}
		stage("build"){
			steps{
				sh "npm --version"
				sh "npm install"
			}
		}
		stage("Test"){
			steps{
				sh "node.js"
			}
		}
		stage("Release the version"){
			steps{
				echo "Release the version"
			}
		}
	}
}