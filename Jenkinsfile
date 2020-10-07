node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("bharat199708/docker-jenkins")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
