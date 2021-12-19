---
layout: post
title:  "I Made My Own Cell Phone"
subtitle: "I Appreciate All The Little iPhone Things Now"
date:   2019-11-11 23:45:13 -0400
background: '/img/posts/red_rocks.png'
---

# Why?

I've had the same iPhone 5S since 2014. It works fine and all phone design changes since the 5S have been negative. Phones are too big now, excessive cameras are obnoxious, and the obsession with the removal of bevels is manufactured to sell us upgrades we don't need -- phones look much worse with a notch or hole in the display for the front camera. In addition, the removal of the headphone jack, home button and fingerprint ID are objective Ls for the user that we must resist. Apple obviously made these changes to sell us more expensive junk or in the case of face ID to justify developing and testing privacy-disrespecting facial recognition.

Unfortunately, AT&T has been sending me emails telling me that they're shutting down their 3G network (which the 5S apparently uses for normal phone stuff even though it uses 4G for data) and telling me that I **must** *buy* a new phone. The audacity.

The newer iPhones are not worth money to me, and Google is even worse about privacy. However I cannot be as legit as my brother and switch the a dumb phone. I need to be able to access the internet. I need the brain augmentation. I looked into the [Light Phone](https://www.thelightphone.com) but it was just a bit too expensive for what you get. Update: I'm also interested in a [Chinese color E-ink phone](https://www.cect-shop.com/en/hisense-a5c.html).

Inspired by [this project](https://learn.adafruit.com/piphone-a-raspberry-pi-based-cellphone), I decided to see if I could make my own phone.

# Design

Here are the main components:

* Waveshare SIM7600A 4G HAT: I can pop my SIM card into this and connect to the cell network to send and receive texts, calls and data.
* Adafruit 3.5" 320x480 TFT touchscreen: for display and IO
* Raspberry Pi Model 3B+: the brains
* My portable USB backup phone battery: for a portable power source. It definitely doesn't give enough enough voltage but still everything seems to work.

And here's what it all looks like (sunglasses for scale)!

![Perfect Cell](/img/posts/perfect_cell.png)

The background here is mostly just for show. I just didn't feel that inspired to make a GUI from scratch so I have to do most things from the terminal, but I at least aliased commands so I don't have to type as much. You pull up the terminal from the terminal icon on the side, and you can open a touch keyboard by touching the shortcut on top of "Settings". You can also access the browser from an icon on the side. Browsing, including checking email, works perfectly well on WiFi or data which already makes this a useful device. I've also been able to send and receive SMS (text) messages using [AT Commands](https://www.waveshare.com/wiki/SIM7600E-H_4G_HAT).  

# Current Status

I've made it to a point where I've demonstrated that it is indeed possible to make your own cell phone that does most smart phone things. This device can text, theoretically it should be able to call, and it can do anything that a normal computer can do with a browser and internet connection. However, to make it usable daily I think I would need to make a LOT of software improvements that just don't feel that exciting to me now that the proof of concept is done. It's not feasible to do almost everything via the terminal or navigating to web pages without a bitter keyboard, automatic zooming, and graphical shortcuts to almost everything. Also, you have to manually check for incoming messages. I'd want to build or integrate an entire messaging client that handles conversations. So for now I'm going to keep using my 5S.

Longer term I really like the idea of a fully modular cell phone that embraces the right to repair by using very common components, and that is all open source and easily customizable by someone who knows what they are doing. Everyone should know what they are doing anyway. There's a bare minimum of system knowledge that is morally required for technology use. Jokes (sort of) aside, the cell phone could be designed to be hand-holdy out of the box, but very open to modification by advanced users. If you ruin your device, you just pay a small fee and mail me the SD card and I'll send you a fresh install. You can pay for a backup service so your SD card will even come with your last stable state pre-installed. Many Linux distros have done a good job of balancing defaults that just work with flexibility. I think a phone like that would have a small butt dedicated market. There is a great-looking [Linux phone](https://puri.sm/products/librem-5/) out there but it's much higher-end. If I started this company it would be called [Perfect Cell](https://dragonball.fandom.com/wiki/Perfect_Cell_Saga) because it kills [Androids](https://dragonball.fandom.com/wiki/Android). I hereby copyright the idea of a cell phone and cell phone company named something like Perfect Cell lol.

# The Latest

Well, my 5S doesn't work anymore, but I held out long enough that AT&T sent me a completely free iPhone 7, so I guess I'll keep kicking the can down the road just a bit more here until I have more free time!
