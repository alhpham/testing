node ('master'){
  stage 'Build and Test'
  checkout scm
  sh 'python $WORKSPACE/simple_py.py'
  sh 'py.test --junitxml $WORKSPACE/simple_py.py'
}
