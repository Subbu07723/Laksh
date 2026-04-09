stage('Push to DockerHub') {
    steps {
        withCredentials([usernamePassword(
            credentialsId: 'dockerhub-creds',
            usernameVariable: 'USER',
            passwordVariable: 'PASS')]) {

            sh 'echo $PASS | docker login -u $USER --password-stdin'
            sh 'docker tag myapp $USER/myapp:latest'
            sh 'docker push $USER/myapp:latest'
        }
    }
}
