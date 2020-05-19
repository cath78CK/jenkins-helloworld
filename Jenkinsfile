node {
    stage('clone') {
       git 'https://github.com/cath78CK/jenkins-helloworld'
     }
    stage('build') {
       bat label: '', script: 'javac Main.java'
     }
    stage('run') {
       bat label: '', script: 'java Main'
     }
}
