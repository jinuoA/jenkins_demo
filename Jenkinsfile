pipeline {
  agent none
  stages {
    stage('Deploy') {
      agent any
      steps {
        echo 'Deploying'
        sh  'chmod u+x deploy_jenkins.sh'
      }
    }
  }
}
