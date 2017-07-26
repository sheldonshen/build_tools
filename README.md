# build_tools

#maven常用命令收集
- mvn compile
- mvn test
- mvn clean
- mvn package
- mvn install //把新创建的jar包安装到仓库中 
- mvn install:install-file -Dfile=i-framework-0.0.1.jar -DgroupId=com.cottsoft -DartifactId=i-framework -Dversion=0.0.1 -Dpackaging=jar
- http://maven.apache.org/plugins/maven-install-plugin/install-file-mojo.html
- mvn archetype:generate //创建新项目
- mvn archetype:generate -DgroupId=com.feidee -DartifactId=hellomaven -DarchetypeArtifactId=maven-archetype-quickstart -Dinteractive=false
- http://maven.apache.org/archetype/maven-archetype-plugin/generate-mojo.html
- mvn archetype:crawl //它会在 C:\Users\buha\.m2\repository目录下生成一个archetype-catalog.xml文件

#gradle常用命令收集

