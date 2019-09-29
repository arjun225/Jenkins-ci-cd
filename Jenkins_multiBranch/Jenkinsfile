node('master') 
{
    stage('ContinuousDownload_Master') 
    {
      git 'https://github.com/selenium-saikrishna/maven.git'
    }
    
    stage('ContinuousBuild_Master')
    {
        sh label: '', script: 'mvn package'
    
    }
    }

