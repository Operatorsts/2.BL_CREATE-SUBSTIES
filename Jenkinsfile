pipeline {
  agent any
  stages {
    stage('erstelle substies') {
      steps {
        sh '/var/lib/jenkins/2BL/configfile/create_substies.sh $SPIELNUMMER $HEIM $GAST'
      }
    }

  }
  environment {
    SPIELNUMMER = '1111'
    HEIM = '"44=1 55=44"'
    GAST = '66=1 '
  }
}