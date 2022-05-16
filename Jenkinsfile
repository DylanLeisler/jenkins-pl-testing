pipeline {
	
	agent none

	stages {

		stage("build") {
			agent {
				docker {
					dockerfile true
					reuseNode true
				}
			}

			steps {
				echo "Build stage here."
				bash ls
			}
		}


		stage("test") {

			steps {
				echo "Testing stage here."
				bash ls
			}
		}


		stage("deploy") {

			steps{
				echo "Deploy stage here."
			}
		}
	}
}