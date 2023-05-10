pipeline {
   agent any
   parameters {
  choice choices: ['dev', 'prod'], description: 'select environment', name: 'ENV'
}

     stages {
      stage ('Working with variables') {
        steps {
       script {
        val1=20
       println "my val1 value is ${val1}"
       println "my parameter value is ${params.ENV}"
       }
      }
      }
     }
}
