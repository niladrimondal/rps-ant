pipeline {
  agent any
  stages {
    stage('Log Ant version info') {
      steps {
        # bat 'ant -version'
        bat 'echo "before checkout"
      }
    }
    stage('GitHub Jenkins Ant Build') {
      steps {
        git 'https://github.com/learn-devops-fast/rps-ant.git'
        # bat 'ant clean compile test package war'
        echo 'echo "after checkout"'
      }
    }
  }
}
