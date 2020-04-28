# Custom Jellyfin CSS (Plug and Play)

## Introduction

This repository contains a whole bunch of little CSS tweaks for the open source media program, [Jellyfin](https://github.com/jellyfin/jellyfin). I initially created these for my server to freshen it up and give it a unique flair, however I think the community would use these best!

This CSS package was designed to be extraordinarily customizable and expandable with ease. By using the CSS variables provided, the entire look and feel can be changed within seconds.

If you have any custom CSS that you would like to add or share, feel free to contribute!

## Code Samples

Example comparison photos of certain "plugins":

#### Original Media Player vs. colored_mediaplayer + blurred_mediaplayer
![](https://i.imgur.com/j527kqG.png)

#### Original vs. plexesque_background
![](https://i.imgur.com/bDIGXyU.png)

#### Original context menu vs. condensed_and_nice_context_menu
![](https://i.imgur.com/h3PYHCD.png)

#### Original "focus" / dialog menu vs. focus_restyle + rounded_focus
![](https://i.imgur.com/bILuR6d.png)



## Installation

# Installation

## Custom CSS Method

[Video Tutorial](https://streamable.com/3j0ej1)

1. Download this repository somewhere on your device, one that has access to the Admin Dashboard in Jellyfin.


2. Navigate to Dashboard -> General -> Custom CSS


3. Copy everything from "copyme.css" to the top of the Custom CSS list.


4. Find the components you want to install, and copy their CSS template into your Custom CSS.


5. Enjoy the custom CSS!

## "Create-A-Theme" Method

[Follow my tutorial on Reddit!](https://www.reddit.com/r/jellyfin/comments/emlwpv/how_to_add_custom_themes_into_jellyfin/)

## Changing Variables

To change variables and make it your own:
1. Open up your .css file either thru Custom CSS or your theme profile depending on how you installed it.
2. Change variables under ":root"

The top few are global variables, which are used by the variables below that, so if you want to change the majority of things, adjust the globals first. If you want to get specific with it, change the "plugin" specific variables below the globals.
