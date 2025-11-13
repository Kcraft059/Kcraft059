<div align="center">	
	
<h1>Hi !... So want to know me a bit more ?</h1>
<img width="1470" height="956" alt="Screenshot 2025-11-13 at 18 14 15" src="https://github.com/user-attachments/assets/f310f5b2-3ba2-4bc0-a9d5-e4d0f45a7518" />

> → _The future \*might be\* declarative._

</div>

## Me

So, as i said, **Hi there !!** </br>
But let's start with a few formalities first:

```yaml
# Few elements about me 
Name: Camille
Pronouns: they/them # TODO: debug genderd.service
Nationnality: 🇫🇷
Age: 16
Languages: # I don't master any of those 
 - C # I'm trying to focus on low-level compiled languages for now
 - Nix # Mainly for env config & dev shells
 - PHP # (alongside other front-end languages like JS)
 - Bash / Zsh
 - Python # I don't use it that much anymore
```
> Yeah… on the moment I thought this would look good… Yeah strange profile for a strange person…

Anyway, I'm Camille, I also go by `Kcraft⁰⁵⁹` online, I'm a french high-school student which codes in their free time. My english isn't perfect, but I love practicing it as much as I love talking to people.</br>
I'm open to all kind of technologies, I'm more interested in low-level programming for now. I use macOS (because it's unix-like) in combination with Nix-Darwin to fully configure my system in a reproducible way.

## My Journey
**But let's start at the beginning of my journey, shall we ?**
<details>
It started relatively simple, an old piece of junk : my `Late 2012 MacMini`. This piece of tech gave me the passion I have today for IT. After few teardowns & rebuilds of this computer, I figured I wanted to try experimenting a bit with it. After making it support new macOS versions, and having installed ubuntu, I started to understand the system more deeply. Tho it was not without mistakes… I did screw-up macOS instances a few time, and made several complete reinstall cycles a few time ^^'</br>
</br>
This is where it took a turn, I discovered nix, a reproducible & declarative package manager (this seemed perfect given how often I reinstalled macos). I made a config… this introduced me the hard way how to actually read documentation & understand the concepts of a language:

```nix
{pkgs, lib, ...} :
{
	service.readme = {
		enable = true;
		config.welcomeMsg = "Nix is steep learning curve… "; # And at the time, the hardest thing I ever done was a for loop in bash
	};
}

```

After I made a config, I saw the world which was openned to me through this package manager, unlimited package access, unlimited tries of anything...</br>
At this point a new thing went into the equation, I developped the idea of making a website, I later got a new laptop (my M3 Mac Book Air).  </br>
</br>
I saw this as an opportunity to turn my old macmini into a server running NixOS. I then made a config, to make a full on home-server with a simple LEMP stack to host my website. In the months following I started to get into code, I started little, with just making some random features, html and css formating etc... but then I started to get into real considerations when I started implementation of a user system, I discovered object oriented programming while doing so, this ended up being a full on framework with identification sytem & database entries. Saddly, I did not implement a front-end yet XD.</br>

```php
<?php
	http_response_code(404);
	echo "Ok… I might have not implemented this yet";
?>
```

Following this experience, I started to wonder if i could get into low-level programming like c, and so I did.</br>
I learned c & hardware-level considerations, which bring us up to today, as I'm writting those lines, with the few little libs I made myself (dynamic array & hashmap implementation).

```c
#include <stdio.h>
#include <stdlib.h>

int main(int argc, char** argv) {
  char* string = malloc(sizeof(char) * 5);
  memcpy(string,"Yeah", sizeof(char) * 5);
  printf("%s, after php, c did taste harder ^^'\n",string);
  free(string);
}
```

So yeah, that's not huge but given how it started a little year ago, I'm quite proud of the few little projects I've made. I know understand OSes, website and programming as a whole a bit more in depth and hope being able to go even further and make a real project one day.
</details>

## Nowadays
**My 'projects' :**

- Low level [programing in C](<https://www.github.com/kcraft059/c-lang-playground>)
- An unfinished [website](<https://ftnetwork.duckdns.org/>)
-	A sketchybar [config](<https://www.github.com/kcraft059/sketchybar-config>)
-	A declarative Nix [config](<https://www.github.com/kcraft059/Nix-Config/>)
-	Help in the transaltion of [Better-Display](<https://www.github.com/waydabber/better-display>)

## TL;DR :

_I'm a silly kid trying to learn IT by themselves, I code on feelings, while never finishing any project and my learning method makes my code a bit unorthodox.
You might just wanna see ppl more talented than me... ^^'_

> [!NOTE]
> If you want to contact me you can do it over Discord[^1], and expect an answer in the near 24h.

## Hardware / OSes

**Oses that I use :**
- [x] MacOS [Main] - managed through Nix-Darwin
- [x] NixOS - For my server
- [x] Windows - only when i'm forced to…
- [ ] Ubuntu - I don't really use it anymore
- [ ] Asahi Linux - _(I hope a release for M3 macs comes out !)_

**My hardware :**
- Laptop : [Arm64] `Macbook Air M3 (2024)`
- Server : [x86] `Mac Mini Late 2012` x2
- _And a lot more junk that doesn't need to be displayed here…_

---


```
	   .-'~~~-.
	 .'o  oOOOo`.
	:~~~-.oOo   o`.
	`. \ ~-.  oOOo.
	  `.; / ~.  OO:
	 .'  ;-- `.o.'
	,'  ; ~~--'~
	;  ;
_ \\;_\\//___\|/_ __  _    _
```
_“As the reality slowly decays… „_


[^1]: Id: @kcraft059, message requests opened.
