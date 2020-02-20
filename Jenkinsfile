node {
    stage('Connect to Git Repository') {
        git 'https://github.com/getraviprakash/postman-CI-demo.git'
      }
      stage('Install NPM') {
            bat 'npm install'
      }
	  stage('Install HTML Extra Reports') {
			bat 'npm install -g newman-reporter-htmlextra'
	  }
      stage('Run API Tests') {
            bat 'npm run api-test'
    }
}