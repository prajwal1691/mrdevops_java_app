@Library('jenkins_shared_lib') _

pipeline{
    agent any
    stages{
        stage('Git Checkout'){
            steps{
                gitCheckout(
                    branch: "main",
                    url: "https://github.com/prajwal1691/mrdevops_java_app.git"
                )
            }
        }

        stage('Unit Test Maven'){
            steps{
                script{
                    mvnTest()
                }
            }
        }

    }
}