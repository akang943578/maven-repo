## 个人maven仓库

### 使用示例：
在需要依赖此公共类库项目的pom里面添加：
```
    <repositories>
        <repository>
            <id>jiakang-maven-repo</id>
            <url>https://raw.githubusercontent.com/haojiakang/maven-repo/master/repository</url>
        </repository>
    </repositories>
```
然后依赖所需要的包即可：
```
    <dependency>
        <groupId>com.david.common</groupId>
        <artifactId>common-code</artifactId>
        <version>${common.version}</version>
    </dependency>
```