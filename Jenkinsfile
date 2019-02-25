pipeline {
    agent any 
    stages {
        stage('continuousdownload_loan') { 
            steps {
                git 'http://github.com/selenium-saikrishna/maven.git'
                 
            }
        }  
    stage('continuousbuild_loan') 
    {
        steps  { 
            sh label: '', script: 'mvn package'
            }
    }
}
}
