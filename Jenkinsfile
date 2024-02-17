pipeline {
  agent any
  stages {
    stage('checkout code') {
      parallel {
        stage('checkout code') {
          steps {
            git(url: 'https://github.com/Yosra-10/wala.git', branch: 'main')
            git(branch: 'main', url: 'https://github.com/Yosra-10/wala.git')
          }
        }

        stage('test') {
          steps {
            sh 'ls -a'
          }
        }

      }
    }

  }
}