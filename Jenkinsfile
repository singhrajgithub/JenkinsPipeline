pipeline {
    agent { docker { image  'node:13.8' } }
    stages {
        stage('Build')           {steps {  sh 'node --version' }}
        stage('Deploy')          {steps {  echo 'Build World' }}
        stage('Test')            {steps { echo 'Build World' } }
    }
    post {    
    always { echo ' i always run ' }
    success { echo ' i always when you are successful' }
    failure { echo ' i always run when you are a failure' }
    
    }
}
