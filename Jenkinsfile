pipeline {
  agent any

  stages {
    
    stage('Clone') {
      steps {
        git url: 'https://github.com/Harshithaaa28/jenkins-simple-demo.git',
            branch:'master'
      }
    }
    
    stage('Run Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh
      }
    }
  }
}
