pipeline {
  agent any
  environment {
    NEW_VERSION = "1.3.0"
    SERVER_CREDENTIALS = credentials('')
  }
  stages {
    stage("build") {
      steps {
        echo "building the application..."
        echo "building version ${NEW_VERSION}..."
      }
    }
    stage("test") {
      steps {
        echo "testing the application..."
      }
    }
    stage("deploy") {
      steps {
        echo "deploy the application..."
        echo "deploy with ${SERVER_CREDENTIALS}"
      }
    }
  }
}
