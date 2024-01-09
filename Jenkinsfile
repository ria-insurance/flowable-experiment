pipeline {
  agent any
  stages {
    stage('Example') {
      steps {
        input {
                message 'setting'
                parameters {
                    string(name: 'value2', defaultValue: env['value1'])
                    string(name: 'value3', defaultValue: env.value1)
                }
            }

      }

  }
}
}
