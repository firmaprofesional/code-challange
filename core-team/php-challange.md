# Core Team Challange

We use PHP pervasive throughout our backend codebase.

## Description

- Create a PHP 7.2 application, using Symfony4 as framwork based on this [architecture file descrition](DefaultArchitecture.pdf).
- This application must have a database of your choice
- Application must be deployable using dockerfile
- Use docker image firmaprofesional/challange [README](https://hub.docker.com/repository/docker/firmaprofesional/challange)
- Please email [Miquel](mailto:mllagostera@firmaprofesional.com) asking for a test certificate working on the docker image provided.

This application must do:
- Create a login page, this page will ask for authentication with certificate
- Recieve the certificate client authentication from Apache [?](http://httpd.apache.org/docs/trunk/mod/mod_ssl.xml)
- Show the information from the certificate [SerialNumber and CN]
- If serial number's certificate didn't exist insert data in database