# use an existing docker image as a base
FROM alpine 

# download and install a dependency
RUN apk add --update redis  
RUN apk add --update gcc 
#tell image what to do when it starts as a container
CMD ["redis-server"]