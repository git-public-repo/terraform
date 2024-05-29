# Jenkines file in branch 02_01
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