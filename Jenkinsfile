pipeline {
    stages {
        stage('Build') { 
            steps {
		sh 'echo starting...'
                sh 'mvn -B -DskipTests clean package' 
		sh 'echo finishing...'
            }
        }
    }
}
