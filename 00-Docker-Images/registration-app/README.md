# Docker build For Registration app
# You'd need to have mvn install
```sh
mvn package
docker build -t kojitechs-registration-app:v1.0.0 . 
docker tag 379ce10c840b  kojibello/kojitechs-registration-app
docker push kojibello/kojitechs-registration-app
```