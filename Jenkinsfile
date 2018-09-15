pipeline {
    agent any
    tools { 
        maven 'Maven 3.5.4' 
        jdk 'Java 1.8' 
    }
    stages {
        stage ('Build') {
            steps {
                sh 'mvn -Dmaven.test.failure.ignore=true install'
            }
        }
    }
}
