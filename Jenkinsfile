pipeline{
    agent {label 'built-in'}
    stages {
        stage('Hello') {
            steps {
                echo 'Hello from Jenkinsfile'
                echo 'Second commit from Jenkinsfile'
            }
        }
        stage('Testing 1') {
            steps {
                echo 'Testing auto build from Jenkinsfile'
            }
        }
        stage('Testing 2') {
            steps {
                echo 'Testing auto build from Jenkinsfile'
            }
        }
    }

}