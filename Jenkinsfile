pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                 bat'mvn install'
            }
        }
        stage("execute"){
            steps{
                bat 'java -jar target/java-project2-1.0-SNAPSHOT.jar'
            }
        }
    }
}
