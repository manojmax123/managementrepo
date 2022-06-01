pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Get code from a GitHub repository
                git url: 'https://https://github.com/manojmax123/managementrepo.git', branch: 'master',
                 credentialsId: 'github_creds'
            }
        }
    }
}
