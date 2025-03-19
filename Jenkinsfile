pipeline {
    agent any
    tools { 
        maven 'mvn'  
    }

    stages {
        stage('SCM') {
            steps {
                echo 'Hello Clone stage'
                 https://github.com/jaswanthBavi/maven-project1.git
                }
        }
        stage('Build') {
            steps {
                echo 'Hello Build'
                sh 'mvn clean install'
            }
        }
        stage('Dev-Deploy') {
            steps {
                echo 'Hello Docker Deploy'
                https://github.com/jaswanthBavi/maven-project1.git  
                  }
        }
}
}
