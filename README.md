# logspout-elk
Simple framework to run logspout with ELK stack to gather docker logs

To use, clone this repo, change into the directory and run a command like:

    docker-compose up --build

Then access http://localhost:5601/ (replacing localhost with the hostname or IP of the docker host if remote).
