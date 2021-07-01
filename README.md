
# ⚠ Please read this before download/using it. ⚠ 
This version used another API to fixes the motd problem with some new features.

And also this version is designed for use on my own server but now is publicly available for everyone.

In original pinger the `motd` placeholder only getting the motd from `server.properties`.

If you don’t need any of these feature or the original version is enough for you to use, you don’t need to switch to this version.

**Still not sure? Recommend you read the [features](https://github.com/HappyAreaBean/Pinger-PAPI-Expansion#features) list first.**

Let me first declare that I did not say that this version is better than the original.
* I may add some feature as requested but I **do not guarantee** that I will add them. 
  * (In most cases, if it takes **little time to add that feature** ~~(and within my abilities)~~, I **might** consider adding)
  * Of course, all the features idea not related to ServerPinger will be rejected.

Feedback / Suggestions always welcome! ❤

---

# ServerPinger

[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/HappyAreaBean/ServerPinger-PAPI-Expansion?label=latest%20stable&style=for-the-badge)](https://github.com/HappyAreaBean/ServerPinger-PAPI-Expansion/releases) [![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/HappyAreaBean/ServerPinger-PAPI-Expansion?include_prereleases&label=latest%20beta&style=for-the-badge)](https://github.com/HappyAreaBean/ServerPinger-PAPI-Expansion/releases) [![GitHub release (latest by date)](https://img.shields.io/github/downloads/HappyAreaBean/ServerPinger-PAPI-Expansion/latest/total?label=Downloads%40Latest&style=for-the-badge)](https://github.com/HappyAreaBean/ServerPinger-PAPI-Expansion/releases)

**PlaceholderAPI Expansion that allows you to ping servers for information**

**Required [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/) plugin to work.** (Why i need to mention this)

**[Wiki](https://github.com/HappyAreaBean/ServerPinger-PAPI-Expansion/wiki)** - **[Configuration](https://github.com/HappyAreaBean/ServerPinger-PAPI-Expansion/wiki/Configuration)** - **[Changelog](https://github.com/HappyAreaBean/ServerPinger-PAPI-Expansion/wiki/Changelog)** - **[Releases](https://github.com/HappyAreaBean/ServerPinger-PAPI-Expansion/releases)**

---

# Features
Lets you ping a server through an IP or domain (with port), to check the online-status and to receive some information.
The placeholders have a "warmup" time of around one or two minutes after installing the expansion.
* MOTD Support
* Dynamic online message
* Boolean online
* [Custom Dynamic](https://github.com/HappyAreaBean/ServerPinger-PAPI-Expansion/wiki/Custom-Dynamic) (Added in v2.1+)

---

# Placeholders List
**Note:** These placeholders have a separate update-delay in the config.yml of PlaceholderAPI

Replace `mycoolserver.com:25565` with your own server/IP.
```
%serverpinger_motd_mycoolserver.com:25565%
%serverpinger_players_mycoolserver.com:25565%
%serverpinger_max_mycoolserver.com:25565%
%serverpinger_pingversion_mycoolserver.com:25565%
%serverpinger_gameversion_mycoolserver.com:25565%
%serverpinger_online_mycoolserver.com:25565%
%serverpinger_booleanonline_mycoolserver.com:25565%
%serverpinger_dynamic_mycoolserver.com:25565%
```

---

# How to install
1. Put `Expansion-ServerPinger.jar` to the folder `plugins\PlaceholderAPI\expansions`
2. /papi reload

---

### Note
* Because the name of the expansion was misleading and confused people about what this expansion does, so now it was renamed to `ServerPinger`
  * ~~Also for better compatibility with the original pinger, so now the identifier is changed to `pinger`.~~

---

### Information about the old version (Status)
**Note:** The expansion name in v2.0 is still called `Status`, please consider to update to the latest version asap
* Starting from version `v2.0`, you only need to use `status` as the placeholder identifier and you don't need to download the two versions separately 

---

I really not confident to publish any project because i'm not really "master" in java coding and i'm scared it will cause some problem so I always don't do this

but I really want to help other server owners who are facing such problems.

So please, please, please if you find any problem please tell me. I will try my best to solve your problem.
