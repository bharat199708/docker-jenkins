node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("bharat123644/docker-jenkins")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
