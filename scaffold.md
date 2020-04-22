# Scaffold参考文档

此项目由[generator-deepexi-spring-cloud](https://github.com/deepexi/generator-deepexi-spring-cloud)生成。

如何你有任何问题或优化建议，请到[Github Issues](https://github.com/deepexi/generator-deepexi-spring-cloud/issues)进行反馈，我们需要你宝贵的意见:-)。

## 项目信息

- **工具版本**: v1.17.0
- **node版本**: v10.13.0
- **yeoman版本**: v2.0.6
- **生成时间**: 2020-04-22 06:50:26
- **生成方式**: 命令模式
- **生成参数**: 
```json
{"groupId":"com.deepexi","artifactId":"deepexi-spring-cloud","basePackage":"com.deepexi","mavenUrl":"http://maven.aliyun.com/nexus/content/groups/public/","templateEngine":"none","log":"logback","jsonParser":"jackson","db":"none","dbPool":"none","orm":"none","discovery":"eureka","feignCircuit":"hystrix","mq":"none","configservice":"none","authentication":"jwt","jwtIssue":"deepexi","security":"shiro","cache":"none","apm":"none","swVersion":"6.4.0","demo":true,"mode":"command","cli":"yo generator-deepexi-spring-cloud -c --groupId=com.deepexi --artifactId=deepexi-spring-cloud --basePackage= --mavenUrl=http://maven.aliyun.com/nexus/content/groups/public/ --templateEngine=none --log=logback --jsonParser=jackson --db=none --dbPool=none --orm=none --discovery=eureka --feignCircuit=hystrix --mq=none --configservice=none --authentication=jwt --jwtIssue=deepexi --security=shiro --cache=none --apm=none --swVersion=6.4.0 --demo=true","version":"1.17.0","basePath":"com/deepexi","conditions":{"eureka":true,"jackson":true,"jwt":true,"shiro":true,"logback":true},"openfeign":true}
```
- **生成命令**: 
```text
yo generator-deepexi-spring-cloud -c --groupId=com.deepexi --artifactId=deepexi-spring-cloud --basePackage= --mavenUrl=http://maven.aliyun.com/nexus/content/groups/public/ --templateEngine=none --log=logback --jsonParser=jackson --db=none --dbPool=none --orm=none --discovery=eureka --feignCircuit=hystrix --mq=none --configservice=none --authentication=jwt --jwtIssue=deepexi --security=shiro --cache=none --apm=none --swVersion=6.4.0 --demo=true
```

## 项目参考

### .gitkeep

项目生成后，为了维持一些空文件夹的存在，会为这些空文件夹添加一个`.gitkeep`文件，如果不需要了，可以在项目目录下执行以下命令全部清除

```bash
$ find . -name '.gitkeep' | xargs rm
```

### demo

可以通过以下指令清除所有带有Demo字样的文件

```bash
$ find . -name '*Demo*' | xargs rm
```
