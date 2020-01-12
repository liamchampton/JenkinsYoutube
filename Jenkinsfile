#!groovy
pipeline {
    agent none
    options {
        timestamps()
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            agent any
            steps {
                sh '''#!/usr/bin/env bash                        
                            echo LiamCodes Jenkinsfile has run successfully!
                        '''
            }
        }
    }

    post {
        success {
            echo 'Build SUCCESS'
        }
    }
}