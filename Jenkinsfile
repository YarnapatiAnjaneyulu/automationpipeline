pipeline {
  agent any 
  stages {
    stage('working with file IO') {
      steps {
        script {
          File myfile = new File("/tmp/newfile.txt")
          myfile.write("Hi Team welcome to Dvs devops")
          println "content is ${myfile.text}"
        }
      }
    }
  }
}
