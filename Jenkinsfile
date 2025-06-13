pipeline {
    agent any

//    triggers {
        cron('* * * * *')
//    }

//    stages {
        stage('Build mavanproject') {
            steps {
                build job: 'mavanproject'
            }
        }

        stage('Build project-2') {
            steps {
                build job: 'project-2'
            }
        }

        stage('Build project-3') {
            steps {
                build job: 'project-3'
            }
        }
    }
}
