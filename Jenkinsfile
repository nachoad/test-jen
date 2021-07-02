pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Aquí estoy metiendo otra línea"
                    echo "Ahora ejecutaré un ls:"
                    ls -lah
                '''
            }
        }
    }
}
