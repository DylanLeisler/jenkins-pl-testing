pipeline {
	
	agent { dockerfile true }

	stages {

		stage("build") {

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