pipeline {
  agent any
  stages {
    stage('Show Vars') {
      steps {
        echo "JENKINS_URL=${env.JENKINS_URL}"
        echo "BUILD_ID=${env.BUILD_ID}"
        echo "BUILD_URL=${env.BUILD_URL}"
      }
    }
  }
}
