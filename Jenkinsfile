pipeline {
    agent any

    tools {
        maven "M398"
    }

    stages {
        stage('echoversion'){
            steps{
                sh 'echo "maven version"'
                sh 'mvn -version'
            }
        }
        // stage('Hello') {
        //     steps {
        //         echo 'Hello World'
        //     }
        // }
    }
}
