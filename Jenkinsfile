pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('artefact') {
      steps {
        ansiColor(colorMapName: 'xterm')
      }
    }

    stage('artefacts') {
      steps {
        touch 'test'
      }
    }

  }
}