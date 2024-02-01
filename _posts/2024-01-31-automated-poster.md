---
layout: single
title: "Automated Poster"
date: 2024-01-31 23:33:27 -0600
categories: experiences
permalink: /:categories/automated-poster
---
This post was made by a Python scipt I made which reads from a text file, creates a Markdown file containing the content of that text file, saves it in the correct local GitHub Repo, and pushes the changes to serve the post on my GitHub Pages site.

I realized 10 minutes into writing this script that this project is kinda useless LMAO. Since I'm writing this in a text file myself anyways, theres no difference to just creating the Markdown file writing directly to it. At least with that I'll be able to actually use the features of Markdown to make the text look nice. If I start writing Markdown in this text file so that it looks nice once it's converted, why not just write Markdown directly in the Markdown file instead?

I figured I'll just finish the project since it was so simple anyways. Maybe in the future I'll come back to it and add more features like specifying your own Front Matter, or maybe a way to style the text so that it looks nicer once converted. The issue with that though is again, why not just write the styling directly in the Markdown? Why even go through a text file at all? A use case I could see with this is if I have a program that creates a bunch of text logs and I can use this script to automatically store those logs on my site.

Anyways, this was a pretty fun project. I got some more practice with opening, reading, and writing files, as well as using the datetime and GitPython libraries. Check out the project code [here][code]!

[code]: https://github.com/eliesercapillar/Jekyll-Static-Site-Auto-Updator
