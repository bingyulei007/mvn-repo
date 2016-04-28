# mvn-repo BingExcel的maven仓库
所有版本目前都放到这里，如果引用可以配置中加入仓库地址
```xml
  <repositories>
		<repository>
			<id>hengyunabc-maven-repo</id>
			<url>https://raw.githubusercontent.com/bingyulei007/maven-repo/master/repository</url>
		</repository>
	</repositories>
```
然后在加入jar依赖即可：
```xml
  <dependency>
			<groupId>com.bing</groupId>
			<artifactId>excel</artifactId>
			<version>1.0-SNAPSHOT</version>
  </dependency>
```
