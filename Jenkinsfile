pipeline {
	agent any
		stages {
			stage('One') {
				steps {
					sh '
						echo "Jenkinsfile Test"
					'
				}
			}


			stage('Two') {
				steps {
					sh '
						echo "Step Two"
					'
				}
			} 

			stage('Three') {
				steps {
					sh '
						echo "Step Three"
					'
				}
			}
		}
}
