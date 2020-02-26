pipeline {
 agent any stages {
  stage('Test') {
   steps {
    sh 'docker run -t postman/newman_ubuntu1404 run https://api.getpostman.com/collections/79156726-fb13-45d7-9260-3fc5331d2e6d?apikey=PMAK-5e3e89a364c2bb002992e41c-3cc11cabe08b3d2a94be7982388d5cb212'
   }
  }
 }
}
