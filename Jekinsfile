node {
    stage('clone') {
        git 'https://github.com/ismailtelhouni/jenkins-helloworld.git'
    }
    stage('build') {
        sh '''
            javac Main.java
            '''
    }
    stage('run') {
        sh '''
            java Main
            '''
    }
}

