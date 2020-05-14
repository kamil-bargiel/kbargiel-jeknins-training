node {
  checkout scm
  properties(
    parameters([
      string(defaultValue: 'John snow', description: 'Who knows nothing?' name:'NAME')
    ])
  )


  stage("Say hi") {
    echo "$[params.NAME]"
  }
}
