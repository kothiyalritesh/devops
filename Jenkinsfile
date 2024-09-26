pipeline {
	agent any
// agent { docker { image 'maven:3.8.7'}
  

		stages{
			stage ('Build'){
				steps {
					//sh 'mvn --version'
					echo "build"
					echo "$PATH"
					echo "BUILD_NUMBER - $env.BUILD_NUMBER"
					echo "BUILD_ID - $enx.BUILD_ID"

				}
			}
		}
}

			// stage ('Test'){
			// 	steps{
			// 		echo "testing"
			// 	}
			// }
			// stage ('Intigration_testing'){
			// 	steps{
			// 		echo "Intigration testing"
			// 	}
			// }
		// post{

		// failure{
		// 	echo "i got failed"
		// }
		// success{
		// 	echo "i got succed"
		// }
		// {
		// 	echo "i got failed"
		// }
		// always{
		// 	echo "i am Awesome"
		// }
		// }
