@Library('jenkins-shared-library') _
pipeline{

    agent any 

    stages {

        
        stage('Gt Checkout'){
            steps {
                script {
                    gitCheckout(branch : "main", url : "https://github.com/aravindav/cicd_java_demo_app.git")
                }
            }
        }
    }
}