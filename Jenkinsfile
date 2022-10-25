pipeline {
    agent 
    {
        node
        {
            label 'deployment'
        }
    }
    stages {
        
        stage('jenkins install')
          {
              steps
              {
                  sh 'chmod +x jenkinsinstall'
                  sh './jenkinsinstall'
                 
              }
          }
        
    }
}
