node {
    stage('Clone') {
        git credentialsId: '8f84d12f-87ff-406d-a9e9-39483d6a1085', url: 'https://github.com/DeKingoye/jenkins-prod-helloworld.git'
    }
    
    stage('Build') {
        sh 'javac Main.java'
    }
    
    stage('Run') {
        sh 'java Main'
    }
}
