---
layout: default
---

## Hi there, and welcome to my maven repo!
  
> If you're not a dev, this page doesn't really apply to you 😔


Example: adding the "Chemistry Lab" mod as a dependency
```groovy
// This should be in your build.gradle file

repositories {
	maven {
		url = 'https://maven.cph101.com/releases'
	}
}

dependencies {
	modImplementation include("chemistrylib:1.0.2") // Remember! This is for Minecraft 1.19.2
}
```
