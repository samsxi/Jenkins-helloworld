node {
    stage('clone') {
        git 'https://github.com/samsxi/Jenkins-helloworld.git'
}
    stage('Build') {
        sh label: '', script: 'javac Main.java'
}
    stage('Run') {
        sh label: '', script: 'java Main '
}
}
