pipeline {
    agent any

    triggers {
        cron('H * * * *')
    }

    stages {
        stage('Build') {
            steps {
                sh '''
                    # Print environment variables
                    printenv
                '''
            }
        }
    }
}
