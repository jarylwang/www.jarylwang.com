---
layout: post
title: Infatuation RO
category: work
tag: web
tags: ragnarok online, private server, website, web design, flux, control panel, eAthena, purple, gray, dark
excerpt: Web Design facelift for Ragnarok Online private game server.
thumb: infatuation-ro.jpg
scheme-text: "#a48cd3"
scheme-link: "#cabce5"
scheme-hover: "#fff"
scheme-code: "#ecde3d"
scheme-bg: "#655673"
---

<p><img src="{{ site.img }}/infatuation-ro.png" alt="InfatuationRO on multiple devices"></p>

<p class=browser>{% picture infatuation-ro-large.png alt="InfatuationRO Web Design" %}</p>

## Skills
- eAthena
- C#
- HTML
- PHP
- Adobe Photoshop
- Server Administration
- People Management

## Background
Back in 2008, I launched a Ragnarok Online (RO) private server, InfatuationRO. The websites then were pretty much chibi/anime themed, which is in line with the graphics style of the game; everything was in light blue or light pink.

There are many private gameservers out in the wild, and I knew that to stand out from the rest, a unique gaming experience with custom stuff exclusive to us, as well as a visually appealing website to attract players is necessary so that we can be the place that they can call home.

## The Approach
A part from the nights spend scripting custom items, NPCs, a website overhaul was needed. It is vital that a website has both form and function (i.e. it should perform as well for as good as it looks). 

### Performance
The majority of the players were from US and Asia, and to ensure that they get the best possible game experience, we had to select a performant VPS to run eAthena, as well as meet the catered budget. A 1GB VPS located in One Wilshire (Datacenter in West Cost, US) was selected after much research. 

### West Coast Location
Being hosted in the US meant that connectivity to US players will be excellent. To add to that, One Wilshire is a renowned location with huge fibre pipelines to many ISPs. Furthermore, it has direct peering with providers such as TaTa, Telia Sonera, and PCCW, which helps give excellent ping (latency) to our Asian players as well.

### Eggs in different basket
Having redundancy is an important part of running a game server. It is paramount that the website and forum remain available to players in the unfortunate event that the game server remain inaccesible.
For that reason, we used a different provider for web hosting. The website runs a Flux Control Panel, which is able to perform a myriad of activities, including but not limited to, game user registration, account management, item database searches. It also runs the forum. To ensure the VPS remain performant, and gaming experience enjoyable, having a seperate web server (many SQL queries running) is necessary.

## Design
Having brainstormed in the name of the private server, Infatuation, we immediately knew that having fancy light colours were not ideal. Instead, we opted to go with a mid-dark purple theme. This immediately meant that we stood out from the flock. We were the first to rock the purple scheme.

I was lucky to have had the opportunity to work with Rory, who is very talented and worked out the majority of the design.

Aside from plain and boring designs, we were also one of the few RO private servers whose site had animated button li rollovers.

We also had a php script that communicates with SQL to return the servers online statuses, as well as the online player count.

I have also configured the front page of the site to pull latest news from the forum feed. This allows our administrators or game masters to save time as they only needed to post in the forums to let players see the news on the website. It also helps make sure news items tally and less redundant.

## Scripting
While I did not do much touching the source code, I have scripted things like custom items, auras, and NPCs. It was a great deal of fun doing so.

## Experience
I took away a lot from the ~1 year of running servers, where I have learnt to manage a team, as well as be responsible for the many players who look forward to logging into the game every day. Of all the projects I have undertaken, Infatuation Ragnarok Online is the one I have learnt the most from, and I am glad I ventured into the world of private game servers.