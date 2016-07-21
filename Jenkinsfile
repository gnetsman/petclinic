
stage 'Build'
node {
    checkout scm
    mvn 'clean compile'
}



def mvn(args) {
    sh "${tool 'Maven 3.x'}/bin/mvn ${args}"
}

