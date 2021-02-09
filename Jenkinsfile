pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo  " barch is $GIT_BRANCH"
            }
        }
        stage('shellcommand') {
            steps {
                sh '''
                whoami
                date
                '''
            }
        }


    }
}