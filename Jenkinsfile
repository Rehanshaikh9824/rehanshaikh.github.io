pipeline{
  agent any

  stages {

    stage ( "git clone") {

      steps {
        git url : 'https://github.com/Rehanshaikh9824/rehanshaikh.github.io.git', branch : 'main'
      }
    }

    stage ("docker image") {
      
         sh "docker --version"
    }
  }
}
