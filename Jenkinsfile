Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image '' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
