pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                sh 'mvn install'
            }
        }
        stage("execute"){
            steps{
                sh 'mv java -jar target/*.jar target/jenkinsfile.jar'
            }
        }
    }
}
