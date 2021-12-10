pipeline {
  agent any
  stages {
    stage('erstelle substies Zeile 1') {
      steps {
        sh 'echo "[${SPIELNUMMER}_subst_dresser]" >> /var/lib/jenkins/2BL/configfile/fb98.cfg'
        sh 'echo "heim_subst_dressnr=${HEIM}" >> /var/lib/jenkins/2BL/configfile/fb98.cfg'
      }
    }

  }
  environment {
    SPIELNUMMER = '1111'
    HEIM = '"44=1 55=44"'
    GAST = '66=1 '
  }
}