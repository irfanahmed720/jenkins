pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('welcome') {
            steps {
                echo 'welcome to india'
            }
        }
        stage('environment') {
            steps {
                echo env.BUILD_ID
                echo env.JENKINS_HOME
                echo env.JOB_NAME


            }
        }
    }
}
