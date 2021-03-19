pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    sh "mkdir pipelineRepo-test"
                }
            }
            stage('Make Files'){
                steps{
                    sh "touch pipelineRepo-test/file1 pipelineRepo-test/file2"
                }
            }
        }
}
