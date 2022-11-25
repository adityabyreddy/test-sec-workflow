pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Test') {
            parallel {
                stage('Unit Tests') {
                    steps {
                        echo 'Hello World'
                    }
                }
                stage('Integration Tests') {
                    steps {
                        echo 'Hello World'
                    }
                }
                stage('Security Unit Tests') {
                    steps {
                        echo 'Hello World'
                    }
                }
                stage('SAST') {
                    steps {
                        echo 'Hello World'
                    }
                }
                stage('SCA') {
                    steps {
                        echo 'Hello World'
                    }
                }
            }
        }
        stage('Verify') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Release') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
