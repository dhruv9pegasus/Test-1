pipeline {
    agent any
environment {
    //set Java _home installation
    JAVA_HOME='C:\ProgramData\Jenkins\.jenkins\jdk-17.0.12'
    //add java bin diectory to path 
PATH="${JAVA_HOME}\\bin;${env.PATH}"}
    tools{
        maven'Maven'}
    stages{
        stage('Getcode'){
            steps{
                git branch:'main',url:https://github.com/dhruv9pegasus/Test-1/edit/main/Jenkinsfile
                    }
        }
    }
}
