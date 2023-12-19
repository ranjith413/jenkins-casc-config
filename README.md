### Build
docker build -t jenkins:jcasc .
### Run
docker run --name jenkins --rm -p 8080:8080 --env ADMIN_PASSWD=1234 jenkins:jcasc  //remove --rm if no need delete container after stop
