pipeline {
    agent any

    triggers {
        pollSCM('* * * * *')
    }

    stages {
        stage('Checkout Git') {
            steps {
                echo 'Pulling...'
                git branch: 'master', url: 'https://github.com/A7mmad2003/ReactExample1.git'
            }
        }
        stage('Display Date') {
            steps {
                sh 'date'
            }
        }
    }
}
