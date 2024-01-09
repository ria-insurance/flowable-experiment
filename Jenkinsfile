pipeline {
  agent any
  stages {
    stage('') {
      steps {
        input(
 id: 'userInput', message: 'Let\'s promote?', parameters: [
 [$class: 'TextParameterDefinition', defaultValue: 'uat', description: 'Environment', name: 'env'],
 [$class: 'BooleanParameterDefinition', defaultValue: true, description: 'Target', name: 'target']
]) 
      }
    }

  }
}
