# peas

## Setup with Maven:

- Using instructions from https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html
- First we run the following command in our project directory:

```shell
mvn archetype:generate "-DgroupId=com.peas" "-DartifactId=peas" "-DarchetypeArtifactId=maven-archetype-quickstart" "-DarchetypeVersion=1.4" "-DinteractiveMode=false"
```

- To install dependencies we can run:

```shell
mvn install
```