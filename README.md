Paper ![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/PaperMC/Paper/Build%20Paper/master)
===========

High performance Paper fork that aims to improve server performance.


**Support and Project Discussion:**
 - [IRC](https://webchat.esper.net/?channels=paper) or [Discord](https://discord.gg/papermc)
 

How To (Server Admins)
------
Paperclip is a jar file that you can download and run just like a normal jar file.

<!--Download Paper from our [downloads page](https://papermc.io/downloads).-->

Run the Paperclip jar directly from your server. Just like old times

  * Documentation on using Paper: [paper.readthedocs.io](https://paper.readthedocs.io/)

How To (Plugin Developers)
------
 * See our API patches [here](Spigot-API-Patches)
 * See upcoming, pending, and recently added API [here](https://github.com/PaperMC/Paper/projects/6)
 * Paper API javadocs here: [papermc.io/javadocs](https://papermc.io/javadocs/)
<!--
 * Maven Repo (for paper-api):
```xml
<repository>
    <id>p4per</id>
    <url>https://repo2.acrylicstyle.xyz</url>
</repository>
```
 * Artifact Information:
```xml
<dependency>
    <groupId>com.destroystokyo.p4per</groupId>
    <artifactId>p4per-api</artifactId>
    <version>1.16.5-R0.1-SNAPSHOT</version>
    <scope>provided</scope>
</dependency>
 ```

**Or alternatively, with Gradle:**

 * Repository:
```groovy
repositories {
    maven {
        url 'https://repo2.acrylicstyle.xyz/'
    }
}
```
 * Artifact:
```groovy
dependencies {
    compileOnly 'com.destroystokyo.p4per:p4per-api:1.16.5-R0.1-SNAPSHOT'
}
```
-->

How To (Compiling Jar From Source)
------
To compile Paper, you need JDK 8, maven, and an internet connection.

Clone this repo, run `./paper jar` from *bash*, get files.

How To (Pull Request)
------
See [Contributing](CONTRIBUTING.md)

Special Thanks To:
-------------

![YourKit-Logo](https://www.yourkit.com/images/yklogo.png)

[YourKit](https://www.yourkit.com/), makers of the outstanding java profiler, support open source projects of all kinds with their full featured [Java](https://www.yourkit.com/java/profiler) and [.NET](https://www.yourkit.com/.net/profiler) application profilers. We thank them for granting Paper an OSS license so that we can make our software the best it can be.
