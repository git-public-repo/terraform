# Jenkines file in branch main
##### test the git changes
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