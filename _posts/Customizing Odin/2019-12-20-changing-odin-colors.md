---
layout: post
title: "Changing Odin Colors"
date: 2019-11-05 08:44:38 -0400
category: customizing-odin
author: mac
short-description: Set Odin colors to your brand colors
---

-----

*This article is a stub, more info coming soon. Colors in Odin are currently a bit messy and need to be cleaned up*

To change the colors used in Odin, first navigate to `_scss/_variables.scss`.

This file contains all of the colors used in Odin. The primary colors you should be concerned about changing are listed below.

**$primary-color** - the main brand color used in Odin. This is used in places such as header background and link colors. 

**$highlight-color** - primarily used for link hover states.

After editing any colors, run `jekyll serve` to see the changes locally. If you're satisfied with your changes, run `jekyll build` and then push your changes to your repo.
