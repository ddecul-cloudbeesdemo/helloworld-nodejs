pipeline {
 agent none
  stages {
    stage('Say Hello') {
      // agent { label 'nodejs-app' }  
      agent { label 'jdk10' }
     steps {
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
  }
}
