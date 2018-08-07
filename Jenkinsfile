@Library ('folio_jenkins_shared_libs@FOLIO-1407') _

buildNPM {
  publishModDescriptor = 'no'
  runLint = 'yes'
  runTest = 'yes'
  runTestOptions = '--karma.singleRun --karma.browsers ChromeDocker --karma.reporters mocha junit --coverage'
  stripesPlatform = 'none'
}
