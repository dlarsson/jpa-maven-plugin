node {
    stage 'Checkout'
    checkout scm

    stage 'Build'
    env.PATH = "${tool 'M3'}/bin:${env.PATH}"
    sh 'mvn clean deploy'
}

