+++
title = 'OurTown_article'
date = 2023-12-29T12:26:09-05:00
draft = true

tags = ['portfolio', 'video games']

showDate = false
showDateUpdated = false
showHeadingAnchors = false
showPagination = false
showReadingTime = false
showTableOfContents = true
showTaxonomies = false 
showWordCount = false
showSummary = false
sharingLinks = false
+++

Header 1
------

<img class="thumbnailshadow" src="img/OurTownLogo_02.jpg"/>

This is a paragraph about Our Town.


{{< gallery >}}
  <img src="img/OurTownLogo_02.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="img/QuestLog.png" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="img/Controls.png" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="img/EveningDrivingAround_02.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="img/StakeOut_02.png" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="img/SchoolDistrict.png" class="grid-w50 md:grid-w33 xl:grid-w25" />
{{< /gallery >}}

Header 2
------

*this text will be itallic*
**this text will be bold**

Summary
------

Our Town is a single-player story-driven investigative horror game set in a small town in 1960's America. You have just arrived in a new town to start working as a newspaper deliverer. However, this seemingly ordinary town holds dark secrets beneath its surface. Deliver newspapers, talk to your neighbors, and explore locations to find evidence and clues as to what is going on in this town.

<img class="thumbnailshadow" src="img/OurTownLogo_02.jpg"/>

Our Town's gameplay consists of day, evening, and night cycles. At the start of each day, players will be able to read the daily paper, which consists of 1960s popular trends and stories about the town. During the day players will deliver newspapers to residents and chat with them. During the evening players have free roam of the town to explore and interact, and at night players can stake out special discovered locations to find evidence of the town’s terrifying mystery. Using newfound evidence, you can then ask the residents about your findings and further the mystery.  

What do you discover through your investigation? What seems like the perfect 1960s American Suburb, is the home of an ancient cosmic entity who controls and feeds on the town’s residents. The entity, like an angler fish, has been using the town to lure people in. You have to find a way to save everyone! But remember; curiosity is not without its consequences. If you aren’t careful, you just might be the next missing person in the paper.


Gallery
------

{{< gallery >}}
  <img src="img/OurTownLogo_02.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="img/QuestLog.png" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="img/Controls.png" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="img/EveningDrivingAround_02.jpg" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="img/StakeOut_02.png" class="grid-w50 md:grid-w33 xl:grid-w25" />
  <img src="img/SchoolDistrict.png" class="grid-w50 md:grid-w33 xl:grid-w25" />
{{< /gallery >}}

Development
------

*Our Town* is an ongoing project which currently has a live demo out. I am the Lead Programmer and Technial Designer for the project working in Unreal Engine 5. Some of the key systems I have created for the game include but are not limited to: 

- Branching Dialogue Trees
- Dynamic Interaction System
- Physics-based Driveable Car
- Day-Night Cycle
- Multiple Endings

My main goal was programming these systems was to create a solid foundation that could be interated upon and improved over time while also being easy to use for artists and developers without having to access complex code and blueprinting. This particularly came into play with the dialogue system. 

*insert images of dialogue spreadsheets*

*Our Town* is heavily dialogue driven, and as such, we needed a system that could easily handle the myriad of different options. Additionally, the writers and artists would need to access this system regularly and be able to quickly understand and implement their dialogue, particularly when it changes. The current system utilizes UE5's Behavior Tree System, along with custom Auxiliary Nodes that impact events based on the player's choices. The advantage of this system is that it provides a visual flow for developers to see how the dialogue might look and feel while playing, while also being simplistic enough that is can be improved and expanded upon with additional custom nodes.

All of these systems were created and tested based upon a pre-established [Game Design Document] (https://docs.google.com/document/d/1PNbGHwb3d4OwsBt54fZowYx2zM2Q0PtfrDAUUiatf3c/edit?usp=sharing) which is being updated and changed as development continued. 

{{< alert "circle-info">}}
check out [ our demo] (https://samvo04.itch.io/our-town) on itchio!
{{< /alert >}}

