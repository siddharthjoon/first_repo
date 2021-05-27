pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                }
        }
    
        stage('show') {
            steps {
                echo 'kkkk'
            }
        }
    }
}
