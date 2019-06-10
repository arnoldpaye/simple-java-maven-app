pipeline {
  stages {
    stage('Build') {
      steps {
        sh 'mvn -B -DskiptTest clean package'
      }
    }
  }
}
