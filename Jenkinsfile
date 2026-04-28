pipeline {
    agent any 
    stages {
        stage("mvn build"){
            steps {
                sh "rm -rf ~/.m2/repository"
                sh "mvn clean package"
            }
        }
    }
}
