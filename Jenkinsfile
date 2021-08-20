def param1 = 'test'
def param2 = 'assignment'

pipeline {
  agent any
  stages {
    stage ("print_var"){
      steps {
        echo "${param1}"
        echo "${param2}"
      }
    }
  }
}
