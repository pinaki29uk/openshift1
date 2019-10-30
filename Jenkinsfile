  pipeline {
    agent {
            label 'maven'
    }
    stages {
      stage('Build') {
        steps {
                git url: 'https://github.com/pinaki1/openshift1.git'
                sh "mvn package -DskipTests"
        }
      }
    }
  }