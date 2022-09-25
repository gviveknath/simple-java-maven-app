pipeline{
    agent any
    stages{
        stage{'bulid'}{
            steps{
                script{
                    checkout([$class: 'GitSCM', branches: [[name: 'pipeline']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/gviveknath/simple-java-maven-app.git']]])

                }
            }
        }
    }
}