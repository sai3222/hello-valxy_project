pipeline {
    agent any

    stages {
        stage('pull') {
            steps {
                git 'https://github.com/sai3222/hello-valxy_project.git'
            }
        }    
        stage('build') {
            steps {
                sh 'mv clean package'
            }    
        }
    }
}
