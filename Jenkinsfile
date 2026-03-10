pipeline{
  agent any
  stages{
    stage('Clone'){
      steps{
        git branch: 'main',
          url : 'https://github.com/Manyaharish14/program3.git'
      }
    }
    stage('Run Script'){
      steps{
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
