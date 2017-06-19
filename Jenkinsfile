pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh '''
                    yarn config set registry 'https://registry.npm.taobao.org'
                    echo yarn complete
                '''
            }
        }
    }
}
