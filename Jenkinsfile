pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                deleteDir()
                git branch: 'main', credentialsId: 'github_pat', url: 'https://github.com/fredericEducentre/jenkins_test_html.git'
            }
        }
    }
}
