pipeline {
  agent any 
  stages {
    stage('working with file IO') {
      steps {
        script {
          def content = readFile 'sample.txt'
echo "Pipeline ran successfully!"

          myfile.write("Hi Team welcome to Dvs devops")
          println "content is ${myfile.text}"
        }
      }
    }
  }
}
