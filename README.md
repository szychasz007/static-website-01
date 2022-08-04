BUILD 
docker build -t szychasz007/first-homework .

RUN
docker run -d --name first-homework --publish 89:80 szychasz007/first-homework

PUSH TO DOCKERHUB
docker push szychasz007/first-homework

KILL CONTAINER
docker kill container_id

CONTAINER LIST
docker ps