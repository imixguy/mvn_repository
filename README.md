# mvn_repository

#1 add repository to pom.xml 
```xml
<repositories>
        <repository>
            <id>mvn-repository</id>
            <url>https://github.com/imixguy/mvn_repository/raw/master</url>
        </repository>
</repositories>
```

#1 add dependency to pom.xml

for node library
```xml
<dependency>
     <groupId>by.imix.cms</groupId>
     <artifactId>node</artifactId>
     <version >1.0.0</version>
</dependency>
```

for node-hibernate library
```xml
<dependency>
     <groupId>by.imix.cms</groupId>
     <artifactId>node-hib</artifactId>
     <version >1.0.0</version>
</dependency>
```

for cmscore library
```xml
<dependency>
     <groupId>by.imix.cms</groupId>
     <artifactId>cmscore</artifactId>
     <version >1.0.0</version>
</dependency>
```

for cmscore-hib library
```xml
<dependency>
     <groupId>by.imix.cms</groupId>
     <artifactId>cmscore-hib</artifactId>
     <version >1.0.0</version>
</dependency>
```

for cmscore-web library
```xml
<dependency>
     <groupId>by.imix.cms</groupId>
     <artifactId>cmscore-web</artifactId>
     <version >1.0.0</version>
</dependency>
```
