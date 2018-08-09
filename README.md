
Build the container
`docker build -t apache-flask .`

Run the container
`docker run -d -p 80:80 --name <name> apache-flask`
`docker run -itd -p 80:80 -v `pwd`/app:/var/www/apache-flask/app --name apache-flask apache-flask`

Alternatively, you can use docker-compose with:
`docker-compose up -d`


Forked from https://github.com/Craicerjack/apache-flask


