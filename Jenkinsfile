node {
    stage('Clone') {
        git 'https://github.com/Ihebkh23/jenkins-helloworld12.git'
    }
    stage('Build') {
        sh '''javac Main.java'''
    }
    stage('Run') {
        sh '''java Main'''
    }
}
