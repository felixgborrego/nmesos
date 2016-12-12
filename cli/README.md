## NMesos CLI

*Deploy projects to Mesos with Singularity!*

Requirements
------------

* Java 8
* Project already Dockerized and published on DockerHub. 


## Release cli

```
sbt it:test
sbt nmesos-cli/assembly nmesos-cli/universal:packageZipTarball nmesos-cli/universal:publish
```

## Release a brew update

Update the Formula `nmesos-cli.rb` with the new public url 
and push the changes to the Master branch.