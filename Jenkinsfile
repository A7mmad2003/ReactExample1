pipeline {
    agent any

    stages {
        stage('Greetings') {
            steps {
                echo 'Initial Stage Complete, your jenkins is working'
            }
        }
        stage('Checkout Git') {
            steps {
                echo 'Pulling...'
                git branch: 'master', url: 'https://github.com'
            }
        }
    }
}
