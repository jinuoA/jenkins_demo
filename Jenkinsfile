pipeline {
  agent none
  stages {
    stage('Deploy') {
      agent any
      steps {
        echo 'Deploying'
        sudo sh './deploy_jenkins.sh'
      }
    }
  }
}
