---
layout: post
date: '2013-12-26 16:54:00 +0000'
categories: Graphic Design
tags:
- Peter Liddle
- British Landscape Artist
- Website
- Kirby CMS
- Twitter Bootstrap
Client:
  Name: Peter Liddle
  Website: www.peterliddle.com
---
Peter Liddle (b.1940) is a British landscape artist and sculptor. He has a large collection of works that he has produced during his long career.

Work involved cataloguing over 500 paintings with name, size, date and material information.

Due to Peter's slow and intermittent internet connection and aversion to technology we decided to develop the catalogue though an excel sheet not an online form.

The site is fully responsive, utilising Twitter Bootstrap. Content is generated very simply using kirby file-based cms. However, I customised it to allow for a centralised image bank and data table in a .csv file.

The accordion menu required the creation of a recursive php script that used some of kirby's native functions to determine if a branch was open and if it contains children.

Visit gist-hub to see the code:

<span class="underline">.csv List Gallery</span><br />
<a href="https://gist.github.com/hagatorn/5554230">https://gist.github.com/hagatorn/5554230</a>

<span class="underline">Accordion Menu</span><br />
<a href="https://gist.github.com/hagatorn/5554164">https://gist.github.com/hagatorn/5554164</a>
