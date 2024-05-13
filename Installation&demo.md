## Installation of Maven:

- Maven 3.9+ requires JDK 8 or above to execute

- make one location on the server to download the maven. for eg./data/build

- Download maven from the https://maven.apache.org/download.cgi
  
```wget https://dlcdn.apache.org/maven/maven-3/3.9.6/binaries/apache-maven-3.9.6-bin.zip```

- once dowloaded the zip file unzip it and copy the bin location - ```/data/build-tools/apache-maven-3.9.6/bin```

- Add the ```/data/build-tools/apache-maven-3.9.6/bin``` directory of the created directory apache-maven-3.9.6 to the ```PATH``` environment variable.

- open ```.bash_profile``` file and set the path.

```
PATH=$PATH:$HOME/bin
export MAVEN_HOME=/data/build-tools/apache-maven-3.9.6
export PATH=$MAVEN_HOME/bin:"$PATH"
export PATH
```
