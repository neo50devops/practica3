pipeline {
  agent any
  stages {
    stage('Install Terraform') {
      steps {
        sh 'apt install wget zip python-pip -y'
        sh 'curl -o terraform.zip https://releases.hashicorp.com/terraform/0.12.5/terraform_0.12.5_linux_amd64.zip'
        sh 'unzip terraform.zip'
        sh 'mv terraform /usr/bin'
        sh 'rm -rf terraform.zip'
      }
    }
  }
}
