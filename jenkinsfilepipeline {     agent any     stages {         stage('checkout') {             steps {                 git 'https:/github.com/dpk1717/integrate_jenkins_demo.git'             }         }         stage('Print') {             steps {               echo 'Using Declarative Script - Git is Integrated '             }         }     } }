pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/dpk1717/integrate_jenkins_demo.git'
            }
        }
        stage('Print') {
            steps {
              echo 'Using Declarative Script - Git is Integrated '
            }
        }
    }
}
