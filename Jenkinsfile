 agent any {
  stages {
    agent none
    stage('Generate Api') {
      steps {
        echo 'Hello, Maven'
        sh 'java -jar swagger-codegen-cli-2.2.1.jar generate -i ~/Documents/swagger.json -l jaxrs'
      }
    }
  }



}