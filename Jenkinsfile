pipeline {
        agent any
        stages {
         stage ('Clean Stage') {
                  steps {
                withMaven(maven : 'maven_3_5_0') {
                   echo 'mvn clean'
        }
    }
}
	stage ('Compile Stage') {
                  steps {
                withMaven(maven : 'maven_3_5_0') {
                   echo 'mvn compile'
        }
    }
}






        stage ('Testing Stage') {
         steps {
                withMaven(maven : 'maven_3_5_0') {
                 echo 'mvn test'
        }
   }
}
        stage ('Deployment Stage') {
         steps {
          withMaven(maven : 'maven_3_5_0') {
          echo 'mvn delpoy'
        }
      }
    }
  }

