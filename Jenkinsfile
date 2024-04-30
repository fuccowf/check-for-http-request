pipeline {
    agent any
    stages {
        stage('Send Request') {
            steps {
                script {
                    def response = sh(script: 'curl -s -o /dev/null -w "%{http_code}" localhost:22890', returnStdout: true).trim()
                    if (response == '200') {
                        echo 'Успешно'
                    } else {
                        error 'Неуспешно'
                    }
                }
            }
        }
    }
}
