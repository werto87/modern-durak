# modern-durak

## Install / Setup
- Download the repository
- Fill out .env file

You can use the nginx.conf file as a template but do not forget to replace {{SERVER_NAME}} with your domain for example myDomain.com

## Run the app
docker-compose down --volumes  && docker-compose pull  && docker-compose up  
Go to your domain you should now get the client served.
