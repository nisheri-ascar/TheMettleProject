---
created: 2024-07-26 06:25
---
tags:: #Daily_note

---
#  📝 Narrative Journal

6:25 AM

Watched Alya yesterday, there's this certain scene that was an idea was presented. The idea of *having an impure motive towards a goal*. 

Thinking about it to myself, I thought "maybe I don't achieve my goals because I'm not being honest to myself.."

I mean, think about it. The reason I started journaling was to impress Carmela, and yet till this day I still go on writing journal. 

Maybe it's okay to have an initial motive that is impure, as long it isn't harming anyone or yourself. And also you leave a good track behind. ^195a0e

5:47 PM

### The mumble server configuration experience 

> Tldr: it was great.. if just mumla the android client just had noise cancelling, it lead me to the worse paths possble

During one of my gaming sessions with my cousins, I faced difficulties of going through their house to play with them. My parents got pissed for me being always absent in home. 

Voice call were my first initial solution so I could finally avoid fleeting everytime I want to play with them, unfortunately we got a mid-entry devices. Messenger or Discord would've kill our phone if we try to run it alongside with Minecraft or any game we wanted to play with.

I searched for some alternatives, and luckily I stumbled across with Mumble; a completely open and selfhosted Voice-Over-IP program. It has many many damn advantages compared to messenger and discord. One is it's low memory usage, low latency thanks to self host (meaning you won't have audio stutter anymore because others are using connection to stream porn in same server..) and pretty simple setup. It had ONE. BIG. PROBLEM. The audio echoing is intensely horrid. 

Things that I tried:
- running Arch Linux/Alpine Linux on chroot
I thought that rolling versions has fix on it (debian provides 1.2.x versions, it's really old..) but only to be greeted with some cryptic C++ linker error. It didn't work.

- using the docker version
No luck with it either, there's a one huge issue that blocks it. With the UID and GID enforcement it was impossible to get virtual mounted volumes to be in docker. It was painful

- compiling it from source
NOPE. NEVER. NOT GONNA DO IT AGAIN.

- trying it on my phone
Same issue with using rolling distros under chroot. It gave cryptic errors.

With all that in mind, I just realized that the client is actually responsible for noise cancelling. The desktop client of Mumble supports noise cancelling though. 

On the other hand, Mumla, the android client has no noise cancelling. There was a thread somewhere in gitlab that talks about integrating noise cancelling from WebRTC, but seems like Mumla is pretty much in maintenance mode these days. No new features will be received. Well that sucks.

I'm thinking that maybe there's a way I can implement the noise cancelling on server side, like maybe filtering the audio stream through pipewire or something? I dunno. But all I can do for now is to finish the two tasks I have left on my list and call it a day. I'll figure out the noise cancelling part in future.

... 

Entirely on different topic now, classes will be on Monday, can't still believe I'd be on HUMMS strand. In Grade 12 I'll try to hover myself back to STEM and hopefully I can handle it. 

---
# 📝 Quick Journal

## Today
#### I did/learned/knew:
- bathed spirit
- cleaned my room
- played Minecraft with cousins
- Broke the PC lolz
#### I'm thankful to:
- .
#### I struggled with:
- waking up to jog
#### I plan to accomplish today:
- I **must** do and I have **responsibility** with it:
- [ ] .
- I only **want/desire** to do when I have free time:
- [ ] .

---

## 🧠☁️ Internal Distractions I have in my mind
- . 

---

## 💡 Fleeting Ideas that crossed in my mind
- . 

---
# 📝 Notes

### Notes/Files created today
```dataview
List FROM "" WHERE file.cday = date("2024-07-11") SORT file.ctime asc
```

### Notes/Files last touched today
```dataview
List FROM "" WHERE file.mday = date("2024-07-11") SORT file.mtime asc
```

---