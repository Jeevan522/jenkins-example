pipeline {

    agent any
    tools {
        maven 'Maven_3.1.0' 
    }
    stages {
        stage('Compile stage') {
            steps {
                bat "mvn clean compile" 
        }
    }

         stage('testing stage') {
             steps {
                bat "mvn test"
        }
    }
        stage('deployment stage') {
              steps {
                bat "mvn deploy"
        }
    }

  }

}
