peline {
    agent any

    stages{
        stage("create zip file"){
            steps{
                script{
            zip middleware-scripts-2$-{BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md   
            }
        }
        
    }
}