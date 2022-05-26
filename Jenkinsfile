def code

node(any) {
 stage('Checkout') {
   checkout scm
}
 stage('Load') {
  code = load 'script.example.groovy'
}
 stage('Execute') {
  code.example1()
}
}
code.example2()
