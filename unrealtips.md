# Unreal Tips

Here are a list of tutorials that I have found useful as I learn Unreal Engine 5.

## Fixing Ugly Shadows in Unreal 5

<iframe width="560" height="315" src="https://www.youtube.com/embed/F3XSKXhIAuU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
[William Faucher](https://youtu.be/F3XSKXhIAuU) is one of my favorite Unreal channels.

## Using Complex Collision as Simple

When your collision isn't working the right way and you'd like to use the vertices of the mesh as your collider (for a photoscanned rock, for example) you can do that! You can also bulk-edit via the Property Matrix. [Here's a link to do both](https://forums.unrealengine.com/t/how-do-i-set-collision-use-complex-as-simple-on-multiple-sm-at-once/284085/6).

<iframe width="560" height="315" src="https://www.youtube.com/embed/VIwYo3J2ez0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
[How to Enable Collisions in Unreal Engine](https://youtu.be/VIwYo3J2ez0) This video is very helpful.

## Creating a Fly-though camera

<iframe width="560" height="315" src="https://www.youtube.com/embed/AFA3xEfh8QI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
[This video](https://youtu.be/AFA3xEfh8QI) explains how to quickly set up a camera rail and to simply animate the camera to look where you like.

<iframe width="560" height="315" src="https://www.youtube.com/embed/GHFq4Dj7sVs?start=403" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
[This video](https://youtu.be/GHFq4Dj7sVs?t=403) explains how to render the sequence.

## Metahumans & LiveLink Face

[This documentation](https://docs.metahuman.unrealengine.com/en-US/animating-metahumans-with-livelink-in-unreal-engine/) from Unreal Engine is easy to follow, AND it no longer requires a depth camera iphone... I used my 2020 iPhone SE tonight to make it work just fine. Very straightforward.

<iframe width="560" height="315" src="https://www.youtube.com/embed/lDFLrzZy2R4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
[This video](https://youtu.be/lDFLrzZy2R4) might be of some use.


## Niagara Particle System

I am having a time trying to find the right level of tutorial for my students. This is the closest I have gotten so far. [CGHOW](https://www.youtube.com/channel/UCN-XH6BI85RG2-Hj7C9oWOw) is the master though!

<iframe width="560" height="315" src="https://www.youtube.com/embed/XnTSE4Vrsz4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
[Common nodes for Niagara](https://youtu.be/XnTSE4Vrsz4)

<iframe width="560" height="315" src="https://www.youtube.com/embed/ivfdCviqS9Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
[CGHOW Getting Started](https://www.youtube.com/watch?v=ivfdCviqS9Y)

<iframe width="560" height="315" src="https://www.youtube.com/embed/wA-pqIybTHc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
Game Study Guide's video on [Making Custom Particle Effects](https://youtu.be/wA-pqIybTHc) helps us use our own sprites, like from the [Kenney.nl Particle Pack](https://kenney.nl/assets/particle-pack).

## Main Menus

When setting up a main menu, the cursor is captured by default. You can [fix that here](https://forums.unrealengine.com/t/show-mouse-cursor-in-bp/379299)! If you need help remembering how to create a UI and show it on the screen, [here you go](https://docs.unrealengine.com/4.27/en-US/InteractiveExperiences/UMG/HowTo/CreatingWidgets/)! TL:DR is *Create Widget* and *Add to Viewport*. [Ben 🌱 UI](https://benui.ca/) knows all the things about UMG.

## Picking Up Objects

<iframe width="560" height="315" src="https://www.youtube.com/embed/R7oLZL97XYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
[How to Select (highlight) other actors/objects by looking at them](https://youtu.be/R7oLZL97XYo) This video was quite good.

<iframe width="560" height="315" src="https://www.youtube.com/embed/t1ECs7CfPNE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
[Basic Inventory](https://youtu.be/t1ECs7CfPNE)

## Dialogue

Some day I would love to figure out [how this system works](https://docs.unrealengine.com/5.0/en-US/using-dialogue-voices-and-waves-in-unreal-engine/).

## Quick Tips

Here are some quick tips.

How to check if the Character is on the ground? Use the [Is Moving on Ground node](https://unrealidiot.com/unreal-engine-4-tutorial-how-to-tell-your-character-is-grounded), from the Character Movement node.