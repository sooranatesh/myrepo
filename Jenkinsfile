pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                    mkdir natesh
                    touch natesh.txt
                    cp natesh.txt /var/jenkins_home/workspace/test2
                    ls -lah
                '''
            }
        }
    }
}
