node {
    stage('scm'){
        git 'https://github.com/dummycode1/spring-petclinic.git'
    }

    
    stage('build'){
        sh 'mvn package'
    }
}