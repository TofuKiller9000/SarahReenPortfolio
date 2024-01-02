+++
title = 'Spit It Out - Week 10 Devlog'
date = 2023-10-25T14:46:30-05:00
draft = false
tags = ['devlogs', 'spit it out', 'programming']
series = [ "Spit It Out Devlog" ]
series_order = 5
showDate = true
showDateUpdated = true
showHeadingAnchors = false
showPagination = false
showReadingTime = true
showTableOfContents = false
showTaxonomies = false 
showWordCount = false
showSummary = true
sharingLinks = false
+++

Programming
------

During this devlog cycle, I focused on trying to get the 2 Player Co-op systems working properly, along with setting things up for the Level Designers to begin testing things out. 

I am using Unity's New Input System for Player Controls. So far it has worked perfectly with single-player, and even just spawning in two characters that are tied to two controllers works. The issue comes in having players select which character they want to play as and then carrying that information over to the next scene with pre-spawned in-player characters. The way that Unity handles identifying controllers is through a component called Player Input. If a player Input is spawned, it ALWAYS has to have an input device connected with it. So while in one scene I can have two-player inputs spawned in contained to two different controllers, I'm having a tough time figuring out the best way to carry those inputs into the next scene. This is still a work in progress, and I'm hoping to get more headway with this before next Monday. 

I also created a video showcasing to the level designers how to start setting up and testing levels. It is a bit jank at the moment due to the problems with spawning in players, but it works for now. I also encountered a couple of bugs with some of the gizmos that I need to iron out once I get the Player Controls working. 

{{< youtube lBxRFhnuaHI >}}

{{< alert "circle-info" >}}
Don't forget to check out [our demo](https://chknlee.itch.io/spit-it-out) on Itchio.
{{< /alert >}}