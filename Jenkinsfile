pipeline {
  agent any
  stages {
    stage('Check GIT') {
      steps {
        git(url: 'https://github.com/cpljudd/MavenTest', branch: 'master', credentialsId: '8cbfba4d111ad96b66ca2afcde7918988bbfb023', poll: true)
      }
    }
  }
}