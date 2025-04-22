pipeline{

    agent any 

    stages {

        
        stage('Gt Checkout'){
            steps {
                script {
                    git branch: 'main', url: 'https://github.com/aravindav/cicd_java_demo_app.git'
                }
            }
        }
    }
}