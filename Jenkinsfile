pipeline {
    agent { docker { image  'node:13.8' } }
    stages {
        stage('Build')           {steps {  sh 'node --version' echo "build"}}
        stage('Deploy')          {steps {  echo 'Build World' }}
        stage('Test')            {steps { echo 'Build World' } }
    }
    
}
