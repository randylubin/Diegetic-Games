---
layout: post
categories: blog
title: Using Figma for Card Game Prototyping
description: A guide to using Figma and Google Sheets to quick prototype a printable
  card game
tags:
- tools
- figma
- prototyping
date: 2020-03-04 08:00:00 +0000

---
This is a guide for using Figma and Google Sheets to rapidly prototype card games. It includes links to the tools, an overview of the key steps, and links to templates. Credit to [Raph D'Amico](https://laughingkaiju.com/ "Raph D'Amico") for discovering this workflow and teaching it to me!

This workflow has some great benefits:

* Access to Figma's powerful design capabilities
* Easy data syncing between Google Sheets and Figma
* Simple printing so you can test your game
* Real time collaboration
* 100% free to use

# The Tools and Resources

[Google Sheets](https://www.google.com/sheets/about/ "Google Sheets") is a free online spreadsheet program. It is easy to use and has powerful function capabilities for generating cards.

[Figma](https://www.figma.com/ "Figma") is a sophisticated online design tool. It is mainly used by web designers but is a great fit for other mediums as well. It's free to use and has a robust community of plugins, designers, and users.

[Google Sheets Sync](https://www.figma.com/community/plugin/735770583268406934/Google-Sheets-Sync "Google Sheets Sync") is a Figma plugin by Dave Williames. It lets you use data from Google Sheets to automatically populate a Figma file. It provides similar functionality to Data Merge in other applications. The plugin has some sophisticated capabilities but we'll be sticking to the basics you can learn more by reading [its documentation](https://www.figma.com/proto/VtXf9HikcehWB7FJrJmApl "Google Sheets Sync Documentation").

[Card Game Figma Template](https://www.figma.com/file/ftN7ORtGVAHgyzjNDO2kAJ/Card-Game-Template?node-id=0%3A1 "Card Game Figma Template") is a Figma file that's all set up for Google Sheets Sync. It currently allows up to 99 cards with fronts and (optional) backs. You can easily extend it beyond 99 cards.

[Example Card Data for Figma](https://docs.google.com/spreadsheets/d/1a7MWX7uyw-oEedgUmydVjk2tpH2iowTptymUVwIg8O0/edit?usp=sharing "Example Card Data for Figma") is a Google Sheet that contains example data for Figma to pull in. You can add more columns of data to customize it for your game.

# Key Steps

1. Create accounts for [Google Sheets](https://www.google.com/sheets/about/ "Google Sheets") and [Figma](https://www.figma.com/ "Figma").
2. Add [Google Sheets Sync](https://www.figma.com/community/plugin/735770583268406934/Google-Sheets-Sync "Google Sheets Sync") to your Figma account by clicking install in the upper left of the page.
3. Duplicate the [Card Game Figma Template](https://www.figma.com/file/ftN7ORtGVAHgyzjNDO2kAJ/Card-Game-Template?node-id=0%3A1 "Card Game Figma Template") and, optionally, rename it with the name of your game. The duplicate option is in the dropdown next to the file's title.

![Duplicate the Figma file by clicking the dropdown next to the file's title and selecting duplicate](/uploads/Screen Shot 2020-03-04 at 2.25.28 PM.png "Duplicate a Figma File")

4. Duplicate [Example Card Data for Figma](https://docs.google.com/spreadsheets/d/1a7MWX7uyw-oEedgUmydVjk2tpH2iowTptymUVwIg8O0/edit?usp=sharing "Example Card Data for Figma") in Google Sheets (File > Make a Copy) and save it under the name of your game.
5. Set the sheet's Sharing permissions to "Anyone with the link can view" – this is essential for enabling the plugin to work.
6. In your Figma file, 

# Further Capabilities

While this guide covers the basics, there are many directions for further exploration, including:

* Advanced Sync capabilities, including Booleans
* A4 formatting for European printers
* Exporting single card files for printer-on-demand services like Game Crafter