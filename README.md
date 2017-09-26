# AEMemo
node{
stage('Check out Code, Prepare environment'){
 sh "node -v"
sh "npm -v"
sh "mvn --version"
}
}
