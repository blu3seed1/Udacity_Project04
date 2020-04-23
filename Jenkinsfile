pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''#!/usr/bin/env sh

## Complete the following steps to get Docker running locally

# Step 1:
# Build image and add a descriptive tag
docker build --tag=app .

# Step 2: 
# List docker images
docker image ls
'''
      }
    }

  }
}