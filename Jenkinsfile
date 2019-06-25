pipeline {
    agent none 
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello, Maven'
                sh 'npm i jquery'
            }
        }
        stage('Example Test') {
            steps {
                echo 'install forever'
                sh 'npm i forever'
            }
        }
    }
}
