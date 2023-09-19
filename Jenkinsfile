pipeline{
    agent {label 'built-in'}
    stages {
        stage('Hello') {
            steps {
                echo 'Hello from Jenkinsfile'
                echo 'Second commit from Jenkinsfile'
            }
        }
        stage('Hello') {
            steps {
                echo 'Testing auto build from Jenkinsfile'
            }
        }
    }

}