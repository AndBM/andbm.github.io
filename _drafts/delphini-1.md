---
title: "Map of Luxembourg post boxes"
collection: projects
type: "Coding project"
permalink: /projects/luxembourg-post-boxes
#venue: "Aarhus University, Department of Math"
date: 2018-10-15
#location: "Aarhus, Denmark"
---

After moving to Luxembourg, I wanted to find the nearest post box. The only resource in this direction was [this website][1], which is not particularly helpful. It gives the addresses of the post boxes sorted alphabetically, which in itself is not as helpful as a map. Since the local address convention is to put street number before street name, the addresses are sorted by street number, which is even less helpful.

I decided to write [some code][2] to scrape the addresses from the website and put them into [Google Maps][3], allowing me to find the nearest post box as well as learning a bit about pulling data from websites.

[1]: https://www.post.lu/en/independants-et-pme/solutions-postales/trouver-une-boite-aux-lettres
[2]: https://github.com/AndBM/luxembourg-postboxes
[3]: https://www.google.com/maps/d/viewer?mid=1jVL1J6kxpNzRxrro8DM2HlKp2ZM0SyAI&ll=49.63663988035693%2C6.146804007843912&z=12
