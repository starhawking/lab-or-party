# lab-or-party
There is no party, only lab. An automated lab.

This repo contains various automation that I use for my home lab. 

My lab can be finiky.
I don't like rebuilding it.
Rebuilding it means I'm not testing on it.
I like automating things. Automation makes my life easier. Automation helps keep me from getting distracted.

# Lab Architecture
My lab is currently based around a pair of somewhat similar HP(E?) DL380 G6's. They are available via iLO2 and have an extra pair of patch cables between them to create a slightly faster network between them. The disks in them are frequently configured in a Raid-0. I value a responsive lab that allows me to iterate faster over a reliable lab. There are usually a pair of disks in a Raid-1 for the root partition to make things a little bit less fragile.

As for the naming scheme, well, I absolutely adore pizza, but it was mainly an uncreative reference to it being a [Pizza Box Form Factor](https://en.wikipedia.org/wiki/Pizza_box_form_factor). Slice just seemed like a good name when I brought the second node on-line.

### Step up sunny, we've got some pizza to eat!
![Stack of SparcStations](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7d/Sparcstack.jpg/220px-Sparcstack.jpg)

Seriously though, I might as well be 12. I can't adaquiately underscore my enthuisiasm for pizza.
