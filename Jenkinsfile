
stage 'Build'
node {
    checkout scm
    mvnw 'clean compile'
}



def mvnw(args) {
    sh "./mvnw ${args}"
}

