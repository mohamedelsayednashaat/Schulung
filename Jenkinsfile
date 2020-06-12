pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing'
      }
    }

    stage('Akzeptanztest') {
      steps {
        echo 'Akzeptanztest durchfuehren'
      }
    }

    stage('Sonarcube Quality Gates') {
      steps {
        echo 'Sonarcube'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Dploying'
      }
    }

  }
}