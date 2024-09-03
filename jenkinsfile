pipeline {
   agent any
   stages {
   stage('Maven Install') {
        steps {
          withMaven(globalMavenSettingsConfig: '', jdk: '', maven: 'maven3', mavenSettingsConfig: '', traceability: true) {
             sh 'mvn clean install'
         }
          
        }
      }
    
    }

}
