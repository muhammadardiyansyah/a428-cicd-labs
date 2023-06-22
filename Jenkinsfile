Node {
  stage('Build') {
    try {
      sh 'npm install'
    }
  }
  stage('Test') {
    try {
      sh './jenkins/scripts/test.sh' 
    }
  }
}
