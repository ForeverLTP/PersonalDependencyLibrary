# PersonalDependencyLibrary
## Maven个人依赖仓库
### 在Pom中资源来源配置如下：

    <repositories>
      <repository>
	  <id>PersonalDependencyLibrary</id> 仓库名称
	  <name>PersonalDependencyLibrary</name>仓库名称
	  <url>https://raw.github.com/ForeverLTP/PersonalDependencyLibrary/master/</url>
          格式：<url>https://raw.github.com/${youtcount}/mvnrepo/master</url>
          注意：master一定要加上
      </repository>
    </repositories>
### Pom依赖如下：
#### 1、Mybatis自动构建model、mapper、xml
                <dependency>
			<groupId>com.hws</groupId>
			<artifactId>MybatisGenerator</artifactId>
			<version>0.0.1-SNAPSHOT</version>
		</dependency>

