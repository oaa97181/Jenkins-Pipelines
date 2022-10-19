pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World 2 :D"'
                sh '''
                    echo "Multiline shell steps works too :D"
                    ls -lah
                '''
            }
        }
    }
}