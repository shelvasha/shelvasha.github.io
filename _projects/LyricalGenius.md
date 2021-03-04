---
layout: post
title: LyricalGenius
description: Get lyrics for your iTunes tracks
img:
---

<img class="col" src="https://github.com/shelvasha/lyricalGenius/raw/master/example.png">

<!-- View on Github Button -->
<a href="https://github.com/shelvasha/lyricalGenius" style=
" border-radius: 25px;
  background-color: #6cc644;
  border: none;
  color: white;
  padding: 10px 30px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;">View on Github
</a>

LyricalGenius is a script Python/Applescript that is able to retrieve Genius lyrics for selected songs in iTunes.

### Pre-requisites

The following are required for the applet to work:

*   subprocess
*   requests
*   bs4
*   BeautifulSoup

These can be installed using `pip install <package>`. For more information, refer to [pip documentation](https://pip.pypa.io/en/stable/installing/).

### Usage

After pre-requisite software is installed, drag thr applet to the iTunes Scripts folder. This should located in the `/Library/iTunes/Scripts` directory. If there is not a Scripts folder in the iTunes directory, create one.

To use the applet, select a track in iTunes, and go to the iTunes scripts menu and select LyricalGenius.

![](/lyricalGenius/example.png){:width="100%"}
