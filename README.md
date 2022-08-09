[![Board Status](https://dev.azure.com/szymonzegzda0535/dc7d0ac3-64e6-4f25-862d-0f202d710792/e390daa2-6992-4ebf-8f87-58b9345e3993/_apis/work/boardbadge/edeb2723-1b9e-4df4-92ba-6926e1eac8ae)](https://dev.azure.com/szymonzegzda0535/dc7d0ac3-64e6-4f25-862d-0f202d710792/_boards/board/t/e390daa2-6992-4ebf-8f87-58b9345e3993/Microsoft.RequirementCategory)
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