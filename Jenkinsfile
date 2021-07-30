pipeline{
	agent any
	stages{
		stage('hello world'){
			steps{
				echo'hello world'
			}
		}
        stage('environment'){
            steps{
            echo "Running ${env.BUILD_NUMBER} on ${env.JENKINS_URL}"
            echo "Running $env.BUILD_NUMBER on $env.JENKINS_URL"
            echo "Running ${BUILD_NUMBER} on ${JENKINS_URL}"
            }
        }

	}

}
