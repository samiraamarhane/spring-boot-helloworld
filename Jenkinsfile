pipeline {
    agent any
    stages {
        stage('SCM') {
            steps {
                git url: 'https://github.com/samiraamarhane/spring-boot-helloworld'
            }
        }
        stage('build && SonarQube analysis') {
            steps {
                
                        bat 'mvn clean package sonar:sonar'
                    }
                }
            }
        }
       
        
