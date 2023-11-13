pipeline {
    agent any
    
    stages {

        stage('run.sh') {
            steps {
                sh '''
                sh run.sh
                '''
            }
        }

        stage('Hello') {
            steps {
                sh '''
                echo "Hi Class, this is a pipeline"
                echo "HEY HEY YOU YOU"
                echo "I DON'T LIKE YOUR GIRLFRIEND"
                '''
            }
            // This is a comment  2
        }
    }
}
