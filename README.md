# Civcraft POM

Work in progress. DO NOT ATTEMPT TO USE YET.

All Civcraft Maven projects should inherit from this pom.

To inherit from this pom, put this into your project's pom.xml:
```
<project>
  ...
  <parent>
    <groupId>co.civcraft.maven</groupId>
    <artifactId>civcraft-pom</artifactId>
    <version>1.0.0</version>
  </parent>  
  ...
  <repositories>
    <repository>
      <id>civcraft-repo</id>
      <url>http://build.civcraft.co:8080/plugin/repository/everything/</url>
    </repository>
  </repositories>
  ...
</project>
```
