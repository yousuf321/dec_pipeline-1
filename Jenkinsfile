pipeline
{
    agent any
    stages
     {
        stage ('cloning the code')
        {
            steps { sh "echo downloading-the-code"  }
        }
 
        stage ('build the code')
        {
            steps { sh "echo building the codeing" }

        }

        stage ('deploy-dev-env')
        {
             steps { sh "echo deploy-dev-env"  }
        }

        stage ('Get approval from QA Lead')
        { 
            steps { input "Please approve for QA deployment?" }
        }

        stage ('deploy-QA-env')
        {
            steps { sh "echo QA-env-deploy" }
        }

     }
}
