pipeline{
    agent any
    stages{
        stage("code"){
            steps{
                git url: "https://github.com/yuvrajlataye750/DEMO-JENKIS-GIT.git", branch: "main"
                input 'yes or no'
            }
        }
        stage("build"){
            steps{
                echo "this is build stage"
            }
        }
    }
}
