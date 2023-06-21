@Library('jenkins_shared_lib') _

pipeline{
    agent any
    stage{
        stage('Git Checkout'){
            steps{
                gitCheckout(
                    branch: "main",
                    url: "https://github.com/prajwal1691/mrdevops_java_app.git"
                )
            }
        }
    }
}