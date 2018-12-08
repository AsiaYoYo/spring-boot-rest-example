pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '/usr/local/maven3/bin/mvn -B -DskipTests clean package'
      }
    }
  }
}