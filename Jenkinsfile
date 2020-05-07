pipeline {
    agent any
    stages {
        stage('ExampleBuild') {
           steps{
              // Run the maven build
              sh 'Hello world'
           }
        }
    }
    post {
        always {
            echo 'toujours hello'
        }
    }
}
