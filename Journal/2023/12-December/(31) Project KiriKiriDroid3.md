
2:41 PM - 3:29 PM

![[Pasted image 20231231144112.png]]

FINALLY IT WORKS!

this took me a while to finished, realizing i wrote something incorrect in the loop part, apparently this part of the code:
```
	ImGui::CreateContext();
	ImGui::Text("Hello World");
	...
```

it was written WAY before the ImGui frame was initiaized, thus probably ImGui was confused and kept crashing, i already ruled out that it wasn't before the initialization/main loop so figured it was somewhere in rendering, and i was right. i left a wrong code firstly when the loop starts.

since i completed writing pretty much the bare bones of a standalone ImGui program, i gotta mess on User Interface stuff. Oh wait what's my goal you say??

## Kiridroid (this name needs some rework fr)
A fork of KirikiriSDL2 aiming to run optimized on Android devices.
Its predecesor is absolute shit, like shit as fuck in terms of performance and ofcourse DAMN PAYWALL.

performance is shit as fuck as it literally uses many many fuckton of layers of displaying literal 2d images, like 15 fuckin fps just to display moving Chocola? What an abomination.

My goal is to eventually port KirikiriSDL2 to android with E-mote engine glued to kirikiri so that nekopara finally works on android, hell yes i want to play catgirls on my phone again.

I thought at first "hmmm maybe krkrsdl2 works without any modification" but nope not at all. krkrsdl2 is not equiped with e-mote engine, the one that mades png moves just like live2d. I figured hm what if i learn c++ and do it myself? and thats where i am today. 

you might asked "whats ImGui for??" well it has two purposes, one is i can learn c++ and two is i can start working with the user interface early as possible. 

### What I know so far

E-mote engine supports android.. unfortunately not for SDL2, things would've be way easier if it did support SDL2 just like Live2d.

What E-mote supports though is [NativeActivity](https://emote.mtwo.co.jp/download/sdk/), as far my knowledge goes its basically directly writing to the display on Android.. it might be slightly difficult to achieve it knowing SDL2 already handles the screen soo...

But hell i digress, nothing is impossible as long i wont give up. I'm certain i can finish this project in next 4 months.

## Project Roadmap

So far here's my roadmap

- [x] Make ImGui work
- [ ] Make a phony user interface for Krkrdroid2
- [ ] Integrate ImGui with existing krkrsdl2 codebase
- [ ] Make E-mote's NativeActivity somehow work with SDL2 beside it.

7:43 PM

![[Pasted image 20231231194334.png]]

this gotta be legit the goofiest ahh thing i ever made in Gimp.

it took me awhile to get things straight again as its been awhile since I touched gimp, and thus this is the rustiest fuck i ever made. 

11:44 PM

Last minute write till I need to write next year again.

I understand now, I understand the sense of new year. Its time to let go.
At exactly 12 AM I will shout and jump and eat an apple, superstition stuff but, its a way to enjoy this celebration.

I need to let go of all these moments in these years, the happiness, the sadness, the best, the worse. Everything is safe in this journal. I have almost all memory written here. But its time to let go, and start a fresh new life in this new year. 

I'm so thankful I exist in such moment, and I will seize this moment.
Its time for a change, its time to let go.

See you next year ;)