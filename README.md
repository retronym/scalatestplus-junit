# ScalaTest + JUnit
ScalaTest + JUnit provides integration support between ScalaTest and JUnit.

**Usage**

To use it for ScalaTest 3.3.0-SNAP3 and JUnit 4.13: 

SBT: 

```
libraryDependencies += "org.scalatestplus" %% "junit-4-13" % "3.3.0.0-SNAP3" % "test"
```

Maven: 

```
<dependency>
  <groupId>org.scalatestplus</groupId>
  <artifactId>junit-4-13</artifactId>
  <version>3.3.0.0-SNAP3</version>
  <scope>test</scope>
</dependency>
```

**Publishing**

Please use the following commands to publish to Sonatype: 

```
$ sbt +publishSigned
```