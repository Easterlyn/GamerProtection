# GamerProtection - A GriefPrevention fork

Stop responding to grief and prevent it instead. GriefPrevention stops grief 
before it starts automatically without any effort from administrators, 
and with very little (self service) effort from players.
Because GriefPrevention teaches players for you, you won't have to publish a
training manual or tutorial for players, or add explanatory signs to your world.

GriefPrevention is compatible with Purpur, Spigot, Paper, and any other implemention of the Bukkit API.

- [Downloads](https://github.com/Easterlyn/GamerProtection/releases)
- [Dev Builds](https://ci.appveyor.com/project/Jikoo/gamerprotection) - Navigate to the Artifacts tab.

## Help and Support

Please do not seek support for GamerProtection in the GriefPrevention repository! Please use [Issues](https://github.com/Easterlyn/GamerProtection/issues) or [Discussions](https://github.com/Easterlyn/GamerProtection/discussions).

---

### Adding GamerProtection as a maven/gradle/etc. dependency

GamerProtection is available via [JitPack](https://jitpack.io/).
```xml
  <repositories>
    <repository>
      <id>jitpack.io</id>
      <url>https://jitpack.io</url>
    </repository>
  </repositories>
```

Replace `${gamerprotection.version}` number with the current version: [![](https://jitpack.io/v/Easterlyn/GamerProtection.svg)](https://jitpack.io/#Easterlyn/GamerProtection)
```xml
    <dependency>
      <groupId>com.github.Easterlyn</groupId>
      <artifactId>GamerProtection</artifactId>
      <version>${gamerprotection.version}</version>
      <scope>provided</scope>
    </dependency>
```

You can also add it to gradle/sbt/leiningen projects. For more information, see https://jitpack.io/#Easterlyn/GamerProtection/

---

[![Weird flex but ok](https://bstats.org/signatures/bukkit/GriefPrevention-legacy.svg)](https://bstats.org/plugin/bukkit/GriefPrevention-legacy)
(Plugin usage stats since version 16.11 - actual use across all versions is larger)
