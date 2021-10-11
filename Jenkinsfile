pipeline {
    agent {
        label 'master'}
    }

    stages {
        stage('Deploy') {
            steps {
                sh 'scp index.html ubuntu@172.31.39.253:/var/www/html/index.nginx-debian.html'
            }
        }
    }
}
