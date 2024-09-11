pipeline {
	agent any
	agent {
    docker {
        image 'maven:3.6.3-openjdk-11'
    }
}

		stages{
			stage ('Build'){
				steps{
					sh "mvn --version"
					echo "Build"
				}
			}
			stage ('Test'){
				steps{
					echo "testing"
				}
			}
			stage ('Intigration_testing'){
				steps{
					echo "Intigration testing"
				}
			}
		}
		post{

		failure{
			echo "i got failed"
		}
		success{
			echo "i got succed"
		}
		{
			echo "i got failed"
		}
		always{
			echo "i am Awesome"
		}
		}

}