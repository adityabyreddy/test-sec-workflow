pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Application Tests') {
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
            }
        }
        stage('Performance Tests') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Security Tests'){
            stages {
                stage('SAST') {
                    parallel {
                        stage('Cppcheck') {
                            steps {
                                echo 'Hello World'
                            }
                        }
                        stage('Flawfinder') {
                            steps {
                                echo 'Hello World'
                            }
                        }
                        stage('Coverity') {
                            steps {
                                echo 'Hello World'
                            }
                        }
                        stage('Snyk SAST') {
                            steps {
                                echo 'Hello World'
                            }
                        }
                    }
                }
                stage('SCA') {
                    parallel {
                        stage('Snyk SCA') {
                            steps {
                                echo 'Hello World'
                            }
                        }
                        stage('Blackduck') {
                            steps {
                                echo 'Hello World'
                            }
                        }
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
