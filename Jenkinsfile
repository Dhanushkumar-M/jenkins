pipeline{
    agent any
    stages{
        stage("Init"){
            steps{
            sh 'echo "Hello world!"'
            }
        }
    }
    post{
        always{
            echo "Pipeline is finished...."
        }
    }
}
