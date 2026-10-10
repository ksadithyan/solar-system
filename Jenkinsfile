pipeline{
    agent any
    tools{
        nodejs "nodejs-26-6-0"
    }
    stages{
        stage("Check The Node Tool Versions"){
            steps{
                echo "Checking the Node and NPM versions"
                sh "node -v"
                sh "npm -v"
            }

        }
    }
}