pipeline {
  agent any

  stages {
    stage('Clone Repository') {
      steps {
        // Explicitly specify the branch you want to checkout
        git url: 'https://github.com/KPkm25/Jenkins_Pipeline.git', branch: 'main'  // or 'master' if that's your default branch
      }
    }
    
    stage('Build') {
      steps {
        sh 'echo "Building the application"'
      }
    }

    stage('Test') {
      steps {
        sh 'echo "Running tests..."'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo "Deploying application"'
      }
    }
  }
}
