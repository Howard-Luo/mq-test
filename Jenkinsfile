pipeline {
    agent {
        any 
    }
    stages {
        stage('Test') {
            steps {
                sh 'oc apply -f buildconfig.yaml'
            }
        }
    }
}