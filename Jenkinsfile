pipeline{
  agent any
  tools{
    maven "Maven_Home"
  }
  stages{
    stage("Build")
    {
      steps{
       dir('prog6') {
            bat 'mvn clean install'
        }}
  }}
}
