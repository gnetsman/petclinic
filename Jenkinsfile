node {
stage "Build" 
    mvnw "clean install -Dbuild.number=${env.BUILD_NUMBER} "

stage "Test"
    mvnw "test"

stage "Publish"
    mvnw "deploy -Dbuild.number=${env.BUILD_NUMBER}"
}


def mvnw(args) {
    sh "./mvnw ${args}"
}
