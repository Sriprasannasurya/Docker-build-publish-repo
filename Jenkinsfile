node {
  checkout scm
  docker.withRegistry('https://registry.hub.docker.com','dockerHub') {
    def buildImage = docker.build("my-image:${env.BUILD_ID}")
    buildImage.push()
  }
}
