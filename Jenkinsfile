#!groovy

stage 'Build'
node {
    checkout scm
    def mvnHome = tool 'Maven 3.x'
   // sh "${mvnHome}/bin/mvn clean install"
}

stage 'Test'
node {
    echo 'hello from Pipeline'
    sh 'docker ps'
}

stage 'Publish'
node {
    echo 'hello from Pipeline'
    sh 'docker images'
}
