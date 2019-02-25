pipeline {
    agent any 
    stages {
        stage('continuousdownload_master') { 
            steps {
                git 'http://github.com/selenium-saikrishna/maven.git'
                 
            }
        }  
    stage('continuousbuild_master') 
    {
        steps  { 
            sh label: '', script: 'mvn package'
            }
    }
}
}
