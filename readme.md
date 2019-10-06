## 🔒 Project Essentials: PermissionsAPI

[![](https://jitpack.io/v/projectessentials/ProjectEssentials-Permissions.svg)](https://jitpack.io/#projectessentials/ProjectEssentials-Permissions)
![GitHub](https://img.shields.io/github/license/ProjectEssentials/ProjectEssentials-Permissions)

> ## Permissions API for Forge mods.

> #### CURRENTLY UNSTABLE VERSION ❗❗❗

#### ❗ Compatibility with forge `28.0.X` version.

## 🧐 Install using Gradle:
> ##### If your project uses Gradle as Build Tool, then use the code below to add dependencies:

```groovy
repositories {
    maven { url("https://jitpack.io") }
}

dependencies {
    compile(
        group: "com.github.projectessentials",
        name: "ProjectEssentials-Permissions",
        version: "v1.14.4-0.1.0.2"
    )
}
```

## 🤔 Install using Maven:
> ##### If your project uses Maven as Build Tool, then use the code below to add dependencies:

```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>

<dependency>
	<groupId>com.github.projectessentials</groupId>
	<artifactId>ProjectEssentials-Permissions</artifactId>
	<version>v1.14.4-0.1.0.2</version>
</dependency>
```

```
Additional information:
    - kotlin-std lib version: 1.3.50
    - kotlinx serialization version: 0.12.0
    - target jvm version: 1.8
```

### After you got the dependencies and the library itself:

# [getting started with read the documentation](./documentation/in-using.md)

### **Note:** this library is written in kotlin, but in java you can work with this API too, but there may be some not beautiful moments. One of these points is that you will see all the properties and fields with internal modifiers (in my library).

> ## Made with 💕 by [MairwunNx](https://mairwunnx.github.io/)