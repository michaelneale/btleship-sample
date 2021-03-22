pipeline {
  stages {
    stage('build in node') {
        agent { 
            dockerfile {
                filename 'Dockerfile.build'
            } 
        }
      steps {
        sh 'echo hello'
      }
    }


    stage('deploy') {
        agent { 
            dockerfile {
                filename 'Dockerfile.deploy'
            } 
        }
      steps {
        sh 'echo hello'
      }
    }


  }
}