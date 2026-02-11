pipeline {
    agent any

    stages {
        stage('Install Tree') {
            steps {
                sh '''
                sudo yum install -y tree
                '''
            }
        }

        stage('Verify Installation') {
            steps {
                sh 'tree --version'
            }
        }
    }
}
