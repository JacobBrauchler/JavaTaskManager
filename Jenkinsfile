 any {
  stages {
    stage('Generate Api') {
      steps {
        echo 'Hello, Maven'
        script 'java -jar swagger-codegen-cli-2.2.1.jar generate -i ~/Documents/swagger.json -l jaxrs'
      }
    }
  }



}