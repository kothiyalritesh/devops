pipeline {
	//agent any
 agent { docker { image 'node:16-alpine'}
  }

		stages{
			stage ('Build'){
				steps {
					sh 'node --version'
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
		}
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

}