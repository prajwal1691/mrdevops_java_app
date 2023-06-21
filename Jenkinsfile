@library('my-shared-lib') _

pipeline {
    agent any 
    
    stages {
        stage('Git Checkout') {
            steps{
                script{
                    gitCheckout(
                        branch: "main"
                        url: "https://github.com/prajwal1691/mrdevops_java_app.git"
                    )
                }
            }

        }
    }
}