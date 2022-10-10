pipeline {
    agent any
    triggers {
    githubPush()
  }
    stages {
        stage('build') {
            steps {
                sh 'echo Hello Jenkins'
            }
        }
    }
}
