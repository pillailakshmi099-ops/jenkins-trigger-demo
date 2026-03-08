pipeline {
    agent any

    triggers {
        githubPush()
        cron('H/2 * * * *')
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
