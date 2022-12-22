@Library('jenkins-library@opensource-release') _
dockerImagePipeline(
  script: this,
  service: 'cmd-admission-webhook-k8s',
  dockerfile: 'Dockerfile',
  buildContext: '.',
  buildArguments: [PLATFORM:"amd64"]
  
)
