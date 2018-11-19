pipeline {
  agent none
  stages {
    stage('git') {
      steps {
        git(url: 'https://github.com/praneeth1989/webapp.git', poll: true, changelog: true)
      }
    }
  }
}