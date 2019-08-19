# Local PG Docker Container

Overview: If you are having trouble running PG locally, you can try to run a docker container with a PG image.

Dependencies:  You will need to download Docker.  Visit https://www.docker.com and follow the instructions for your OS.

Directions:
Once you have Docker installed and running on your machine, clone this repo and in the root of the directory run:

`docker-compose up`

Once the PG container has started successfully, you can minimize it and it should behave just the same way that a local installation of PG would.

If you want to run the PG container in a detached mode (running in the background and you won't have to keep your terminal open) then you can run `docker-compose up --detach` instead of just `docker-compose up`.

When you are finished, you can stop the PG container with the command `docker-compose down`.  The data should still be preserved however, and you should be able to start right where you left off again when you are ready to do a `docker-compose up`.

