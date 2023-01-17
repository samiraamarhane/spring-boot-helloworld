node {    
       stage('SonarQube analysis') {
       // requires SonarQube Scanner 2.8+
       def scannerHome = tool 'SONAR_RUNNER';
       withSonarQubeEnv('SonarQube') {
            bat "\"${scannerHome}\\bin\\sonar-scanner.bat\""
       }
}
        
