pipeline {
  agent {
    docker {
      image 'hashicorp/terraform'
    }

  }
  stages {
    stage('') {
      steps {
        sh 'terraform init'
      }
    }
  }
}