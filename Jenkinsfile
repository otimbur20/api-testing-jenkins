pipeline {

    agent any

   stages {

	stage('Collection') {
           steps {
              sh 'newman run TestAPI.postman_collection.json -e stgx.postman_environment.json'
           }

    }
   }
}