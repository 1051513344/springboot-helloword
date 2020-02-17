pipeline {
   agent any

   stages {
      stage('publish project') {
         steps {
            deploy adapters: [tomcat9(credentialsId: 'e7d70443-03bf-4cd7-8829-11ee64730489', path: '', url: 'http://fwq.geekrabbit.xyz:3074/')], contextPath: null, war: 'target/*.war'
         }
      }
   }
}