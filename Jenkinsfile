pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Goodbye') {
            steps {
                echo 'Goodbye World'
            }
        }
        stage('HelloFromPowerShell') {
            steps {
                powershell 'Write-Output "Hello PowerShell"'
            }
        }
    }
}
