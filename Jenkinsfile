pipeline {
    agent any
    triggers {
        buildTrigger(token: 'sometoken')
    }
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
