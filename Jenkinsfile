# Jenkines file in branch main
# test to run workflow
pipeline {
    agent {lable "linux"}
    options {
        buildDiscarder logRotator(artifactDaysToKeepStr: ", artifactNumToKeepStr: '5', daysToKeepStr: ", numToKeepStr: '5' )
        disableConcurrentBuilds()
    }
    stages {
        stage('Hello') {
            steps {
                echo "hello"
            }
        }
    }
}