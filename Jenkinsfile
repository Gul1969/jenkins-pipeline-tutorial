pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    sh "mkdir ~/jenkins-turorial-test"
                }
            }
                stage('Make File'){
                        steps{
                           sh "touch ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
                        }
                }
         }
}
