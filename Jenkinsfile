node ('MAVEN_JDK8') {
    stage('vesion control') {
        git 
        url: https://github.com/FullDevOps/game-of-life.git,
        branch: 'srcripted'
    }
    stage('build') {
        sh 'export PATH="/usr/lib/jvm/java-1.8.0-openjdk-amd64/bin:$PATH" && mvn package'
    }
}