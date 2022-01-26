---
layout: page
title: Frequently Asked Questions
permalink: /faq/
---

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

I created this FAQ because it became impossible for me to answer every mail I get. Most of the technical issues i am being asked about are usually user-driven problems.

Please be aware that I won't answer mails about issues that are listed here unless they are distinctly special / different.

dreamDroid is a private project and it's about programming. During the last year it started more and more to consume most of the time I wanted to spend on it for supporting "errors" that mostly could've been found by oneself.

This FAQ is alive and will be extended whenever I feel it should be.


## Where do I configure a connection?
It's called "Profiles" (short for Connection Profiles). Long tap to change/delete.

## Streaming doesn't work, what am I doing wrong?
* First of all. Streaming is still an experimental feature. Please  don't rate the app based on wether streaming works for you or not. There are plenty of reasons why streaming may not work with your android device (e.g. because it's to old and slow) which I simply cannot control.<
* Once you see the player Controls, dreamDroid is completely out of the game. DreamDroid only passes the streaming URL to a player that can handle it. If you have more than one you'll see a standard android dialog for picking one, try several if the first doesn't work. Everything that happens after the URL has been passed is handled by the player (e.g. VLC or MX Player).
* Turn off "streaming authentication" in the webinterface setup.
* If streaming often stops suddenly for you, please update your Dreambox firmware. There is a new streamproxy (the small piece of software which forwards dreambox live-tv to the network) which fixes that issue. Here's the changeset.
* Streaming is more reliable on LAN
* You might just not be able to stream HD content without stuttering. Many times it doesn't work at all.
On almost all android devices you will have to use a 3rd party player like the VLC for Android Beta (which I usually recommend) or MX Player or one of the many others capable of playing "most" of the stuff out there. Namely the required codecs are MPEG2 SPTS for SD and H264 SPTS for HD. Both use a http transport.
* You need a proper WLAN Signal Quality.
* Use a "LAN" based Connection Profile without anything entered in the grey "Streaming Settings" section of a connection Profile to test streaming. If nothing's there the default settings, which should be fine for pretty much every dreambox out there, will be applied.
*Do not change settings you don't understand, it will most likely break more than it fixes

## 1 Star on Play store, I'll give you 5 when it does support enigma1.
You downloaded the wrong tool. dreamDroid was cleary written for enigma2 based Dreamboxes.
Please reconsider rating the app at all just because you didn't read the app description. <br>
It's a matter of respect, right?

## It doesn't work!
Is your Device a dm500hd, dm800, dm800se, dm7020hd or dm8000? If not, dreamDroid does not or not fully support it!

## I am using OpenWebIf and dreamDroid does not (always) work as expected!
Anything but genuine Dreamboxes with a genuine Web Interface is unsupported

## When will you add support for OpenWebIf?
Never. They added an API-Clone of the genuine Web Interface. They have to fix ANY issue that isn't around with the official Web Interface.

## dreamDroid is broken, connecting doesn't work. I checked everything twice, Settings are 100% OK!
In the past, exactly 100% of these cases there have been errors in the settings or the basic connectivity between the android device and the dreambox. Sometimes there have been blanks where they shouldn't be (preferably after dots).
I can ensure you that there are no technical connection issues caused by dreamDroid.
It works for over 100000 Users, and it uses standard android functionality to do the connectivity stuff. Check your settings and connectivity again. Check if you can open the Web Interface using any android Browser. If it still doesn't work ask people in a forum to assist you.

## Will you please add feature xyz?
Probably. Probably not. Feel free to mail me feature requests but please be warned that you usually won't get any response. You can be sure that I'll read your message, though!

## I've got a patch, can you merge it?
Generally: Yes, sure! I'd glady take any help i can get!
But be warned, I do not blindly merge pull-requests. I may even be a little picky about it ;). If you want to avoid wasting your time contact me before you start.
I simply have certain expectations on code quality and about what dreamDroid should become and what it shouldn't. Please respect that.

## Are you pissed?
Not at all, just out of time!
