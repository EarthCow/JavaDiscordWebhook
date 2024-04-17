Provides a way to add @k3kdude's [DiscordWebhook](https://gist.github.com/k3kdude/fba6f6b37594eae3d6f9475330733bdb) class with [my modifications](https://gist.github.com/EarthCow/8933c4140de9c97527b7a804621f657a) as a maven dependency using [jitpack](https://jitpack.io/p/jitpack/example).

My modifications fixed the encoding issue via `StandardCharsets.UTF_8`, made the classes public, made some variables final, and added timestamp functionality.

```xml

<repositories>
  ...
  <repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
  </repository>
  ...
</repositories>

<dependencies>
  ...
  <dependency>
    <groupId>com.github.EarthCow</groupId>
    <artifactId>JavaDiscordWebhook</artifactId>
    <version>{current_version}</version>
  </dependency>
  ...
</dependencies>
```

Make sure you replace `{current_version}` with the current release version here on github.
