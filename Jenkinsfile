pipeline {
    agent any
    stages {
      stage ('checkout stage') {
        steps {
           git 'https://github.com/Amit-4535/today03092025.git'
        }
      }
      stage ('build stage') {
        steps {
           echo "building stage"
        }
      }
      stage ('test stage') {
        steps {
           echo "running test stage"
        }
      }
      stage ('running the script') {
        steps {
           sh './script.sh'
        }
      }
    }
}
