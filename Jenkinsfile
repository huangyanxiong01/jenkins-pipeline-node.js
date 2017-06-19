pipeline {
    agent { docker 'node' }
    stages {
        stage('build') {
            steps {
                sh '''
                    yarn config set registry 'https://registry.npm.taobao.org'
                '''
            }
        }
    }
}
