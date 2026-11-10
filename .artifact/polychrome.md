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
    caption: The sidebar beside a Wikipedia article, with four pinned tabs as icons at the top and the other tabs in groups named Computing, Machines and Navigation
    alt: A narrow sidebar listing four pinned site icons and three colored tab groups of Wikipedia articles, with Ada Lovelace highlighted, beside the open Ada Lovelace article
  - src: sidebar.png
    caption: The sidebar beside a Chrome window, with pinned tabs as icons and tab groups named Docs and News
    alt: A Chrome window on a bulldog page, with a sidebar to its left listing pinned icons and tab groups named Docs and News
unconfirmed:
  - date
---

Polychrome is a Chrome extension that lists open tabs and tab groups in a sidebar at the left edge of the browser window. The README explains that Chrome now unloads background tabs on its own, so many tabs can stay open, and the horizontal tab strip has little room for them.

Pinned tabs appear as a row of icons at the top of the sidebar, and the other tabs are listed under their groups. A group can be archived to a bookmarks folder and restored later. The search field looks through open tabs, history and bookmarks. A menu removes duplicate tabs and discards background tabs.

The sidebar is a separate popup window, 256 pixels wide, which the extension opens beside the browser window. Polychrome is at version 0.9.9 and is loaded unpacked from the repository in Chrome's developer mode. The last code change was in August 2022.

JavaScript, Mithril, Chrome Manifest V3. 2021.
