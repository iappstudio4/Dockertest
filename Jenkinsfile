node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("iappstudio4/Dockertest")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
