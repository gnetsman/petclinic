
stage 'Build'
node {
    checkout scm
    mvn 'clean compile'
}



def mvnw(args) {
    sh "./mvnw ${args}"
}

