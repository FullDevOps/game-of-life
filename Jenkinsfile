node('MAVEN_JDK8') {
    stage('version control') {
        git url: 'https://github.com/khajadevopsmarch23/game-of-life.git',
            branch: 'scripted'
    }
}
    stage('build') {
        sh 'export PATH="/usr/lib/jvm/java-1.8.0-openjdk-amd64/bin:$PATH" && mvn package'
    }
}