# service-config
Configuration service, this project contain the configuration files of the following projects:

[company-service](https://github.com/YassirLAAR/company-service "company-service")

### How to run correctly

#### Create Configuration

Using Git Bash, run the following commands

```sh
$ cd ~
$ mkdir cloud-conf
$ touche cloud-conf\application.properties
$ touche cloud-conf\company-service.properties
``` 

Once the two files created, Update them with configuartion test data:
application.properties:

    xParam=687
    
application.properties:

    yParam=862
    me=yassir.laaroussi@outlook.com
    server.port=8081
    

Then back to the Git Bash:
```sh
$ cd cloud-conf
$ git add . 
$ git commit -m "First Config"
```

#### Running the application

If you're using eclise, go to the class **ServiceConfigApplication** and run it as JavaApplication

#### Testing the application

In a browser, use this url to restor configurations:
* http://localhost:8888/application/master 
* http://localhost:8888/company-service/master
