pipeline {
    agent { docker { image  'node:13.8' } }
    stages {
        stage('Build')           {steps {  sh 'node --version' }}
        stage('Deploy')          {steps {  echo 'Build World' }}
        stage('Test')            {steps { echo 'Build World' } }
    }
    
}
