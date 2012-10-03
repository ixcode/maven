# maven-pom

This is a maven pom file that you can use as a base for yours so you don't have to replicate lots of maven knowledge.

To Use - create a `pom.xml` in project folder with the following definition:

    <project>
        <modelVersion>4.0.0</modelVersion>

        <parent>
            <groupId>org.ixcode</groupId>
            <artifactId>maven-pom</artifactId>
            <version>1.0-SNAPSHOT</version>
        </parent>

        <groupId>your.organisation.id</groupId>
        <artifactId>your-artifact-name</artifactId>
        <version>1.0-SNAPSHOT</version>
        <packaging>jar</packaging>

        <url>http://your.company.url</url>


        <dependencies>
           <!-- put yer deps in ere! -->
        </dependencies>
    </project>


# Installation:

Right now theres no repo available so you'll need to do this:

    $ git clone git@github.com:ixcode/maven-pom.git
    $ mvn install

# To Do:

integrate the failsafe plugin for integration testing (http://maven.apache.org/plugins/maven-failsafe-plugin/)
