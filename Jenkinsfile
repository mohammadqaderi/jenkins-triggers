pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Build Completed"'
        git branch: 'main', url: 'https://github.com/mohammadqaderi/vprofile.git'
      }
    }
  }
}
