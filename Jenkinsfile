pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo "Hello world"
            }
        }
        stage('test') {
            steps {
                echo 'Tested!' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployed!' 
            }
        }
    }
        post{
            always{
                echo 'completed'
            }
            success{
                echo 'success'
            }
            failure{
                echo 'failure'
            }
        }
}
