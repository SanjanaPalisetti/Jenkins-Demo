pipeline {
    agent any

    tools {
        maven "maven"
    }

    stages {
        stage('Print Hello') {
            steps {
		echo "Hello World"
            }

            }
        }

  post {
        failure {
		echo "Application failed ***********" 
        }

    }    

}

