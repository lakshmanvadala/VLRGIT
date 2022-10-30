pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build App'
            }
        }
        stage('Test') {
            steps {
                echo 'Test App'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy App'
            }
        }
        
        
    }
    post
    {
        always
        {
            emailext body: 'This is the first pipeline', subject: 'pipeline status', to: 'lakshman@gvpcew.ac.in'
        }
    }
}
