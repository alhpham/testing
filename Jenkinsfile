node ('master'){
  stage 'Build and Test'
  checkout scm
  sh 'python $WORKSPACE/simple_py.py'
  sh 'nosetests --with-xunit $WORKSPACE/simple_py.py'
}
