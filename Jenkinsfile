pipeline{
    agent any

    tools {
         maven 'maven'
         jdk 'java'
    }

    stages{
        
        stage('build'){
            steps{
               sh 'mvn package -Dmaven.test.skip=true'
            }
        }
    }
}
