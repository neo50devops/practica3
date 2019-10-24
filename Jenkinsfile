pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '''sudo apt install wget zip python-pip -y
curl -o terraform.zip https://releases.hashicorp.com/terraform/0.12.5/terraform_0.12.5_linux_amd64.zip
unzip terraform.zip
sudo mv terraform /usr/bin
rm -rf terraform.zip'''
      }
    }
  }
}