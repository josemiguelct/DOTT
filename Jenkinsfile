pipeline {
	agent any
		stages {
			stage('Build') {
				steps {
					sh '''
						echo "Jenkinsfile Test"
					'''
				}
			}


			stage('Test') {
				steps {
					sh '''
						echo "Step Two"
					'''
				}
			} 

			stage('Deploy') {
				steps {
					sh '''
						echo "Step Three"
					'''
				}
			}
		}
}
