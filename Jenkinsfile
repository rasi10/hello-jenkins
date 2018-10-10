node {
    stage('Checkout') {
        checkout scm
    }

    stage('Directory/Location') {
        sh 'pwd'
        sh 'ls -lart'
    }
    
    stage('Make the file executable') {
        sh 'chmod 777 hello.sh'
    }
    
    stage('Running the file') {
        sh './hello.sh'
    }
    
    stage('Checking Robot') {
        sh 'robot hello.robot'
    }
}
