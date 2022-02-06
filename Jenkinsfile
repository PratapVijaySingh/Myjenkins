pipeline {
    agent any

    stages {
        stage('Git pull source code') {
            steps {
                git branch: 'main', url: 'https://github.com/PratapVijaySingh/test1.git'
            }
        }
        stage('Compile source') {
            steps {
                bat ''' cd /D D:\\Learning\\localgitrepo
                npm install '''
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
