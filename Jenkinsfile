pipeline {
    agent {label 'MASTER'}
    stages {
        stage('Source'){
            steps {
                git 'https://github.com/dummycode1/spring-petclinic.git'
            }
        }
        stage('Package') {
            steps {
                sh 'mvn package'
            }
        }
    }
}

