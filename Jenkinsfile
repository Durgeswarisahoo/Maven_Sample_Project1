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
                sh 'java -jar java-project2.jar'
            }
        }
    }
}
