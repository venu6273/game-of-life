node('JDK8'){
    stage('source code'){
        git branch:'master',url:'https://github.com/venu6273/game-of-life.git'
    }
    stage('build the code'){
        sh 'mvn package'
    }
    //stage('archiving and test results'){
      //  junit '**/surefire-report/*.xml'
        //archiveArtifacts artifacts: '**/*.war', followSymlinks: false
    //}
}