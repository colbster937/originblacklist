# OriginBlacklist

basically just a reimplementation of originblacklist but for eaglerxserver

> [!WARNING]
> **Velocity is the main platform I'm developing this for, bungee & bukkit will still work but will probably have some bugs and will receive less support!**

### Features
- [x] Origin Blacklisting
- [x] Brand Blacklisting
- [x] Username blacklisting
- [x] Custom kick message
- [x] Custom blacklist MOTD
- [x] MiniMessage formatting for messages
- [x] Velocity, *Bungee, and *Bukkit support
  <br>_<sub><span style="color:gray">Bungee and Bukkit are should work, but have bugs.</span></sub>_
- [x] Send blacklists to a discord webhook
- [ ] Blacklist subscription URLs
- [ ] Simple blacklist command
- [ ] Blacklist -> Whitelist
- [ ] IP blacklisting
- [ ] Update system

### Download
**[https://github.com/colbster937/originblacklist/releases/latest/](https://github.com/colbster937/originblacklist/releases/latest/)**

### Building
```
$ git clone https://github.com/colbster937/originblacklist.git
$ cd originblacklist
$ gradle wrapper
$ ./gradlew shadowJar
```
