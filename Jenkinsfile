node {
   stage('Preparation') {
      git 'https://github.com/finiteprods/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}