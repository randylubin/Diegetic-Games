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

![Card Prototyping in Figma](/uploads/Screen Shot 2020-03-04 at 3.37.47 PM.png "Card Prototyping in Figma")

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

[Card Game Figma Template](https://www.figma.com/file/ftN7ORtGVAHgyzjNDO2kAJ/Card-Game-Template?node-id=0%3A1 "Card Game Figma Template") is a Figma file that's prepared for Google Sheets Sync. It currently set for up to 99 cards with fronts and (optional) backs. You can easily extend it beyond 99 cards.

[Example Card Data for Figma](https://docs.google.com/spreadsheets/d/1a7MWX7uyw-oEedgUmydVjk2tpH2iowTptymUVwIg8O0/edit?usp=sharing "Example Card Data for Figma") is a Google Sheet that contains example data for Figma to pull in. You can add more columns of data to customize it for your game.

# Key Steps

1) Create accounts for [Google Sheets](https://www.google.com/sheets/about/ "Google Sheets") and [Figma](https://www.figma.com/ "Figma").

2) Add [Google Sheets Sync](https://www.figma.com/community/plugin/735770583268406934/Google-Sheets-Sync "Google Sheets Sync") to your Figma account by clicking install in the upper left of the page.

3) Duplicate the [Card Game Figma Template](https://www.figma.com/file/ftN7ORtGVAHgyzjNDO2kAJ/Card-Game-Template?node-id=0%3A1 "Card Game Figma Template") and, optionally, rename it with the name of your game. The duplicate option is in the dropdown next to the file's title.

![Duplicate the Figma file by clicking the dropdown next to the file's title and selecting duplicate](/uploads/Screen Shot 2020-03-04 at 2.25.28 PM.png "Duplicate a Figma File")

4) Duplicate [Example Card Data for Figma](https://docs.google.com/spreadsheets/d/1a7MWX7uyw-oEedgUmydVjk2tpH2iowTptymUVwIg8O0/edit?usp=sharing "Example Card Data for Figma") in Google Sheets (File > Make a Copy) and save it under the name of your game.

5) Set the sheet's Sharing permissions to "Anyone with the link can view" – this is essential for enabling the plugin to work. Then copy the shareable link.

![Set sharing to anyone with the link can view](/uploads/Screen Shot 2020-03-04 at 2.41.17 PM.png)6) In your Figma file, set up Google Sheets Sync by clicking Menu > Plugins > Google Sheet Sync.

![](/uploads/Screen Shot 2020-03-04 at 2.43.13 PM.png)

7) Paste your Google Sheets view sharing URL into the pop-up and select 'Update entire document' and then click Fetch & Sync.

![](/uploads/Screen Shot 2020-03-04 at 2.43.01 PM.png)

The cards in Figma should now populate with data from your spreadsheet. You'll need to re-run Fetch & Sync every time you update your data in Google Sheets – don't forget to choose 'Update entire document'.

# Customizing the Design and Data

The Figma file is set up so that the pages of cards draw from one Component card template for each side of the card. These are located left of the pages.

![Edit Component](/uploads/Screen Shot 2020-03-04 at 3.21.17 PM.png "Edit Component")

Any changes you make to the Card Component will affect the actual cards embedded in the pages to the right. Figma offers a robust suite of design tools to change color, font, layout, and more. I recommend keeping things simple and in black and white for early stage playtests.

You can add additional columns of data to Google Sheet but you'll need to update the Card Component to pull those values in. Do so by creating a new text element in the Card Component and giving it a tile "#ColName" where ColName is the name of the new column in Google Sheets – capitalization and spaces are ignored. Make sure the column title is in bold font.

# Printing

Once your Figma file has the right design and the correct data, export to PDF by clicking Menu > File > Export Frames to PDF.

![Export to PDF](/uploads/Screen Shot 2020-03-04 at 3.32.59 PM.png "Export to PDF")

Before you print, make sure to delete any empty pages, including the backs, if you aren't using them. If your cards are two sided but your printer doesn't print duplex, you'll have to print the first 11 pages and then feed the fronts back into the printer and then print pages 12-22.

Consider getting a paper cutter ($10 USD) to speed up the card creation:

* [AmazonBasics Paper Trimmer](https://amzn.to/3cw9kGn "Paper Trimmer")
* [Japanese Corner Clipper](https://amzn.to/32Vp5lJ "Japanese Corner Clipper") (rounded corners)

# Further Capabilities

While the template is set up for simple black and white cards, you can get quite sophisticated with your designs. Raph used this approach to make our cards for Dungeon Court and they turned out great!

![](/uploads/IMG_3542.jpeg)

While this guide covers the basics, there are many directions for further exploration:

* Advanced Sync capabilities, including Booleans
* A4 formatting for European printers
* Exporting single card files for printer-on-demand services like Game Crafter