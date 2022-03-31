pipeline {
    agent any

    stages {
        stage('Verify Branch') {
            steps {
                env.GIT_BRANCH = sh(script: "git rev-parse HEAD", returnStdout: true).trim()
                echo $GIT_BRANCH
            }
        }
    }
}