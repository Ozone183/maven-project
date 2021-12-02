# maven-project
maven-project with jenkins
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
    <modelVersion>4.0.0</modelVersion>
    <packaging>pom</packaging>

    <parent>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-parent</artifactId>
        <version>2.2.0.M4</version> <!-- lookup parent from repository -->
    </parent>
    <groupId>org.apache.maven.archetypes</groupId>
    <artifactId>simple_maven_project</artifactId>
    <version>1.0</version>
    <name>simple_maven_project</name>
    <description>Blank multi project for Spring Boot + Elm</description>


    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>org.apache.maven.archetypes</groupId>
                <artifactId>simple_maven_project-frontend</artifactId>
                <version>1.0</version>
            </dependency>
            <dependency>
                <groupId>org.apache.maven.archetypes</groupId>
                <artifactId>simple_maven_project-backend</artifactId>
                <version>1.0</version>
            </dependency>
        </dependencies>
    </dependencyManagement>

    <repositories>
        <repository>
            <id>spring-snapshots</id>
            <name>Spring Snapshots</name>
            <url>https://repo.spring.io/snapshot</url>
            <snapshots>
            </snapshots>
        </repository>
        <repository>
            <id>spring-milestones</id>
            <name>Spring Milestones</name>
            <url>https://repo.spring.io/milestone</url>
        </repository>
    </repositories>
    <pluginRepositories>
        <pluginRepository>
            <id>spring-snapshots</id>
            <name>Spring Snapshots</name>
            <url>https://repo.spring.io/snapshot</url>
            <snapshots>
            </snapshots>
        </pluginRepository>
        <pluginRepository>
            <id>spring-milestones</id>
            <name>Spring Milestones</name>
            <url>https://repo.spring.io/milestone</url>
        </pluginRepository>
    </pluginRepositories>
<modules>  <module>simple_maven_project-frontend</module>
    <module>simple_maven_project-backend</module>
  </modules>
</project>
[kunle@vps-a751aa87 simple_maven_project]$
[kunle@vps-a751aa87 simple_maven_project]$ cat pom.xml
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
    <modelVersion>4.0.0</modelVersion>
    <packaging>pom</packaging>

    <parent>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-parent</artifactId>
        <version>2.2.0.M4</version> <!-- lookup parent from repository -->
    </parent>
    <groupId>org.apache.maven.archetypes</groupId>
    <artifactId>simple_maven_project</artifactId>
    <version>1.0</version>
    <name>simple_maven_project</name>
    <description>Blank multi project for Spring Boot + Elm</description>


    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>org.apache.maven.archetypes</groupId>
                <artifactId>simple_maven_project-frontend</artifactId>
                <version>1.0</version>
            </dependency>
            <dependency>
                <groupId>org.apache.maven.archetypes</groupId>
                <artifactId>simple_maven_project-backend</artifactId>
                <version>1.0</version>
            </dependency>
        </dependencies>
    </dependencyManagement>

    <repositories>
        <repository>
            <id>spring-snapshots</id>
            <name>Spring Snapshots</name>
            <url>https://repo.spring.io/snapshot</url>
            <snapshots>
            </snapshots>
        </repository>
        <repository>
            <id>spring-milestones</id>
            <name>Spring Milestones</name>
            <url>https://repo.spring.io/milestone</url>
        </repository>
    </repositories>
    <pluginRepositories>
        <pluginRepository>
            <id>spring-snapshots</id>
            <name>Spring Snapshots</name>
            <url>https://repo.spring.io/snapshot</url>
            <snapshots>
            </snapshots>
        </pluginRepository>
        <pluginRepository>
            <id>spring-milestones</id>
            <name>Spring Milestones</name>
            <url>https://repo.spring.io/milestone</url>
        </pluginRepository>
    </pluginRepositories>
<modules>  <module>simple_maven_project-frontend</module>
    <module>simple_maven_project-backend</module>
  </modules>
</project>
[kunle@vps-a751aa87 simple_maven_project]$ ls
[kunle@vps-a751aa87 simple_maven_project]$ cat pom.xml
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
    <modelVersion>4.0.0</modelVersion>
    <packaging>pom</packaging>

    <parent>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-parent</artifactId>
        <version>2.2.0.M4</version> <!-- lookup parent from repository -->
    </parent>
    <groupId>org.apache.maven.archetypes</groupId>
    <artifactId>simple_maven_project</artifactId>
    <version>1.0</version>
    <name>simple_maven_project</name>
    <description>Blank multi project for Spring Boot + Elm</description>


    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>org.apache.maven.archetypes</groupId>
                <artifactId>simple_maven_project-frontend</artifactId>
                <version>1.0</version>
            </dependency>
            <dependency>
                <groupId>org.apache.maven.archetypes</groupId>
                <artifactId>simple_maven_project-backend</artifactId>
                <version>1.0</version>
            </dependency>
        </dependencies>
    </dependencyManagement>

    <repositories>
        <repository>
            <id>spring-snapshots</id>
            <name>Spring Snapshots</name>
            <url>https://repo.spring.io/snapshot</url>
            <snapshots>
            </snapshots>
        </repository>
        <repository>
            <id>spring-milestones</id>
            <name>Spring Milestones</name>
            <url>https://repo.spring.io/milestone</url>
        </repository>
    </repositories>
    <pluginRepositories>
        <pluginRepository>
            <id>spring-snapshots</id>
            <name>Spring Snapshots</name>
            <url>https://repo.spring.io/snapshot</url>
            <snapshots>
            </snapshots>
        </pluginRepository>
        <pluginRepository>
            <id>spring-milestones</id>
            <name>Spring Milestones</name>
            <url>https://repo.spring.io/milestone</url>
        </pluginRepository>
    </pluginRepositories>
<modules>  <module>simple_maven_project-frontend</module>
    <module>simple_maven_project-backend</module>
  </modules>
</project>
