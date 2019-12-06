pipeline{
  agent any
  stages{
    stage('English'){
      steps{
        sh 'echo "In English, we say Hello World"'
        }
    }
    stage('French'){
      steps{
        sh 'echo "En France, on dit, salut tout le monde"'
        }
    }
    stage('Other languages'){
      steps{
        sh '''
          echo "Hola el mundo"
          echo "Ciao el miendo"
          ls -lah
        '''
      }
    }
  }
}
