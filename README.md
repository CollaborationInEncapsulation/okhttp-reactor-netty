# okhttp-reactor-netty

# How to use
  
## Gradle Dependency

```gradle

dependencies {
  compile 'com.github.CollaborationInEncapsulation:okhttp-reactor-netty:master'
}

repositories {
  maven { url 'https://jitpack.io' }
}
```

## Integration with OkHttp3

```java
ReactorNettyCallFactory nettyCallFactory = new ReactorNettyCallFactory();
OkHttpClient client = new OkHttpClient();
client.setCallFactory(nettyCallFactory);
client...
```
