scala_library(name='scala',
  provides = scala_artifact(
    org = 'com.twitter',
    name = 'util-core',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty/jvm/org/scala-lang/modules:scala-parser-combinators',
    'util/util-function/src/main/java',
  ],
  sources=rglobs('*.scala')
)
