pipeline {
    agent any

    stages {
        stage('Git pull source code') {
            steps {
                git branch: 'main', url: 'https://github.com/PratapVijaySingh/test1.git'
            }
        }
        stage('Build source') {
            steps {
                bat ''' cd /D D:\\Learning\\localgitrepo
                npm install '''
            }
        }
        
         stage('Testing') {
            steps {
                echo 'Testing Completed'
            }
        }
        stage('Release') {
            steps {
                echo 'Release done'
            }
        }
    }
}
