pipeline{
    agent any;
    stages{
        stage("Code Quality"){
            steps{
                sh 'echo checking code quality'
            }
        }
        stage("Util testing"){
            steps{
                sh 'echo Testing the application'
            }
        }
        stage("Build"){
            steps{
                sh 'echo Create application package'
            }
        }
        stage("Delivery"){
            steps{
                sh 'echo Uploading the artifact to a repository'
            }
        }
        stage("Deploy"){
            steps{
                sh 'echo Deploying the application'
            }
        }
    }
}