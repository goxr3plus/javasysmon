# Newer version -> [javasysmon2](https://github.com/goxr3plus/javasysmon2)

[![HitCount](http://hits.dwyl.io/goxr3plus/javasysmon.svg)](http://hits.dwyl.io/goxr3plus/javasysmon)

# How to add it on your Maven Project ?

For them [follow this tutorial to add them to your Local Maven Repository](https://www.mkyong.com/maven/how-to-include-library-manully-into-maven-local-repository/) 


For example (for JAVASYSMON) in my computer i do the following :

> mvn install:install-file -Dfile=D:\GitHub\XR3Player\localLibraries\javasysmon-0.3.6.0.jar -DgroupId=local.github.goxr3plus -DartifactId=javasysmon -Dversion=3.6.0 -Dpackaging=jar

Then add it on the dependencies like this:

```XML
<!-- javasysmon -->
<dependency>                                      
	<groupId>local.github.goxr3plus</groupId>     
	<artifactId>javasysmon</artifactId>           
	<version>3.6.0</version>                      
</dependency>                                     
```

**Download the .jar file i added on releases** , because if you use JitPack you will get the wrong .jar which produces errors .


# Bug free version of  [jezhumble/javasysmon](https://github.com/jezhumble/javasysmon)
A correct version of javasysmon without bugs , all the forks of JavaSysmon have bugs or don't work on Windows 7 [ This is a mix of several jar files i found and maked a one in all pack :) ] . 

Using it in various projects until JavaSysmon Repository resolves the bugs (maybe they never fix it....) .

