pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
             stage('Build') {
            steps {
                echo 'Building'
            }
        }
             stage('Stage Deploy') {
            steps {
                echo 'Stage deploying'
            }
        }
             stage('QA Release') {
            steps {
                echo 'Releasing to QA'
            }
        }
               stage('Production Release') {
            steps {
                echo 'Releasing to Production'
            }
        }
    }
}
