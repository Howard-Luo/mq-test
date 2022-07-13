pipeline {
    agent any
    stages {
        stage('Testing') {
            steps {
                sh 'oc apply -f buildconfig.yaml'
            }
        }
    }
}
