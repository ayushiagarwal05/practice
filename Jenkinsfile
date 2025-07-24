pipeline {
    agent any
    parameters {
        string(name:'NAME', defaultValue:'', description: 'Enter your name')
    }
    stages {
        stage('build') {
            steps {
                echo "Hello ${params.NAME} app"
            }
        }
    }
}
