//@Library('jira9')_
pipeline{
agent any 
stages{
  stage('Collect Issue Summary'){
            steps {
                script{
                   collect-issue-summary()
                       }
                  }
             }
      } 
}
