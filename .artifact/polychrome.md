---
title: Polychrome
date: 2021-05
category: product
tags:
  - browser-extension
links:
  source: https://github.com/arfct/polychrome
media:
  - src: sidebar-wikipedia.png
    caption: The sidebar beside a Wikipedia article, with four pinned tabs as icons along the top and the rest under groups named Computing, Machines and Navigation
    alt: A narrow sidebar listing four pinned site icons and three colored tab groups of Wikipedia articles, with Ada Lovelace highlighted, beside the open Ada Lovelace article
  - src: sidebar.png
    caption: The sidebar to the left of a Chrome window, its tabs under groups named Docs and News
    alt: A Chrome window on a bulldog page, with a sidebar to its left listing pinned icons and tab groups named Docs and News
unconfirmed:
  - date
---

Polychrome's README observes that Chrome now unloads background tabs on its own, which makes it worthwhile to keep a great many open, and that the tab strip has no room for them. The extension lists them down the left edge of the browser. Its sidebar is a separate popup window 256 pixels wide, and where the screen has no space to the left of the browser, the browser window is narrowed by 256 pixels to make room.

In the first image the sidebar stands beside a Wikipedia article. Four pinned tabs form a row of icons at the top, and the other tabs are listed under their groups. Archiving a group closes its tabs and saves them as bookmarks in a folder named after the group, from which it can be restored later. The search field looks through open tabs, then history and bookmarks. A menu removes duplicate tabs and puts background tabs to sleep.

Version 0.9.9 is loaded unpacked from the repository in Chrome's developer mode. The last code change was in August 2022.

JavaScript, Mithril, Chrome Manifest V3. 2021.
