pipeline {
    agent any
    stages {
        stage('ExampleBuild') {
           steps{
              // Run the maven build
              echo 'Hello world'
           }
        }
    }
    post {
        always {
            echo 'toujours hello'
        }
    }
}
