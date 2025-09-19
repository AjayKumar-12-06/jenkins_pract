pipeline{
    agent any
        stages {
            stage('test') {
                steps{
                    script{
                        
                        sh """
                            echo "This is test build"
                        """
                    }
                }

            }
            stage('build') {
                steps{
                    script {
                        sh """
                            echo "This is build"
                        """
                    }
                }

            }
            stage('deploy') {
                steps{
                    script{
                        sh """
                            echo "this is deploy"

                        """

                    
                    }
                }
            }
        }
    }
