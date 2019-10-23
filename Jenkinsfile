pipeline {
  agent {
    docker {
      image 'hashicorp/terraform:latest'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'terraform init'
      }
    }
  }
}