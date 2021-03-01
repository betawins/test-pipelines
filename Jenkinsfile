pipeline {
 agent any
 stages  {
  stage ("gitcheckout")
  {
  git 'https://github.com/betawins/test-pipelines.git'
  }
 stage("Build") {
 steps {
 echo "Some code compilation here..."
 }
 }
 stage("Test") {
 steps {
 echo "Some tests execution here..."
 echo 1
 }
 }
 }
}
