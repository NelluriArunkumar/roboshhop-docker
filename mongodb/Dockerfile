FROM mongo:7.0
COPY *.js /docker-entrypoint-initdb.d

##In above we are copyinng the .js file from local to image default path, so that it will automatically load the data when we run it.