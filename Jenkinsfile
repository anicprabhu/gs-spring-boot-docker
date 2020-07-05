pipeline { 
    agent any  
    stages { 
        stage('Build') { 
            steps { 
               echo 'This is a minimal pipeline.' 
               git 'https://github.com/anicprabhu/gs-spring-boot-docker.git'
               sh 'cd gs-spring-boot-docker'
               sh 'mvn clean install'
            }
        }
    }
}
