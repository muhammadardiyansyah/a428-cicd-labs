Node {
  stage('Build') {
    try {
      sh 'npm install'
    }
    catch (exc) {
      echo 'Something failed'
      throw
    }
  }
  stage('Test') {
    try {
      sh './jenkins/scripts/test.sh' 
    }
    catch (ext) {
      echo 'Something failed'
      throw
    }
  }
}
