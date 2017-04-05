  docker-compose up

Enter `http://0.0.0.0:5000/` in a browser to see the application running.

Because the application code is mounted into the container using a volume, you can make changes to its code and see the changes instantly, without having to rebuild the image.


  docker-compose up -d

  docker-compose ps

to see what environment variables are available to the web service:

  docker-compose run web env

  docker-compose stop

  docker-compose down --volumes
