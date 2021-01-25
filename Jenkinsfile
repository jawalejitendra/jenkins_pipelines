node {
        stage('Build') {
            sh('echo this is building the application')
        }

        stage('Test') {
            sh('echo this is testing the application')
        }

        stage('Deploy') {
            echo 'this is deploying the application'
        }
        
        post ('Clean Workspace') {
                always {
                        cleanWs()
                }
        }
}
