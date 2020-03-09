
node {
    stage('clone') {
       git credentialsId: '6abb4d1b-1b52-4666-93ed-ecac2126494f', url: 'https://github.com/gueyebabacar/jenkins-helloworld.git'
    }
     stage('build') {
        sh label: '', script: 'javac Main.java'
    }
     stage('run') {
        sh label: '', script: 'java Main'
    }
}
