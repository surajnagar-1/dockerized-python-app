pipeline{
    agent any
    stages{
       stage("Code clone") {
         steps{
                git url: "https://github.com/surajnagar-1/dockerized-flask-app.git", branch:"main"
            }
        }
    
        stage("Build") {
            steps{
                sh "docker build -t flask-app ."
            }
        }
    
        
        
        stage("Push to docker hub"){
            steps{
                withCredentials([usernamePassword( 
                    credentialsId:"dockerhubCreds",
                    passwordVariable:"dockerpass",
                    usernameVariable:"dockeruser"
                )]){
                sh "docker login -u ${env.dockeruser} -p ${env.dockerpass}"
                
                sh "docker image tag flask-app ${env.dockeruser}/flask-app"
                
                sh "docker push ${env.dockeruser}/flask-app:latest"
                }
            }
        }
    
        stage("Deploy") {
            steps{
                sh "docker compose up -d"
            }
        }
    }
}
