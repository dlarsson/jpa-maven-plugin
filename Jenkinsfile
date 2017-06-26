node {
    stage 'Build'
    env.PATH = "${tool 'Maven'}/bin:${env.PATH}"
    sh 'mvn clean deploy'
}

