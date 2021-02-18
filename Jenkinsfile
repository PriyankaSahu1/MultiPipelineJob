pipeline {
	agent any
	
	stages {
		stage ('Compile Stage') {
		
			steps {
				sh '''
			cd student_app
			mvn clean install
		'''
			}
		}
	stage ('Testing Stage') {

            steps {
                echo 'testing the application'
            }
        }


        stage ('Deployment Stage') {
            steps {
                echo 'deploying the application'
            }
        }
     }
}​​​​​
