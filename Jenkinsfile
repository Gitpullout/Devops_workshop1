pipeline {
    agent {
        node{
            label 'maven-agent'
        }
    }
    stages {
        stage('clone code') {
            steps {
                git branch: 'main', url: 'https://github.com/Gitpullout/Devops_workshop1.git'
            }
        }
    }
}
