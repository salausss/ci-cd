pipeline {
  agent any
  environment {
    secret = CREDENTIALS('test-user-test')
  }
  stages {
    stage ('cred-call') {
	  steps {
	    sh 'echo $secret'
	  }
  }
  }
    }
