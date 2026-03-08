pipeline {
    agent any

    triggers {
        githubPush()
        
    }

    stages {
        stage('Build') {
            steps {
                echo 'Build Stage Running'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Stage Running'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy Stage Running'
            }
        }
    }
}
