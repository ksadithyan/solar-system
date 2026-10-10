pipeline{
    agent any
    tools{
        nodejs "nodejs-26-6-0"
    }
    stages{
        stage("Check The Node Tool Versions"){
            steps{
                sh "node -v"
                sh "npm -v"
            }

        }
    }
}