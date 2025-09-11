node {
    // some block
    stage('clone') {
        git branch: 'jenkins', url: 'https://github.com/dehnbekale/jenkins.git'// some block
    }
    stage('build') {
        sh 'javac Main.java'
    }
    stage('run') {
        sh 'java Main'
    }
}
