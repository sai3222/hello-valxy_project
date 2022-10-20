pipeline {
    agent any

    stages {
        stage('pull') {
            steps {
                sh 'git clone https://github.com/sai3222/hello-valxy_project.git'
            }
        }    
        stage('build') {
            steps {
                sh 'package'
            }    
        }
    }
}
