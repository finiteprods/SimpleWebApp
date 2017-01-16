node {
   stage('Preparation') {
      git 'https://github.com/finiteprods/SimpleWebApp.git'
   }
   stage('Build') {
      bat "./gradlew clean test"
   }
}