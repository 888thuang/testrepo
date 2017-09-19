pineline {
    agent { docker 'python:3.5.1' }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World"'
		sh 'python --version'
                sh '''
		   echo " Multiple shell steps works woo"
		   ls -lah
		   '''
            }
        }
    }
}







