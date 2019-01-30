node('master')
{
   stage('Continuous Download')
    { 
       git 'https://github.com/thrinadhp/scripted.git'
     }
    stage('Continuous Build')
     {
       sh 'mvn package'
      }
}
