---
layout: post
title: My own Keynote theme
date: 2025-01-22 18:06 +0100
tags: design ipad keynote
---

Unlike Jekyll, Keynote, Apple's presentation software, has beautiful default themes (or _Designs_).
But I still like the design of my website, and wanted to use it for my presentations too.

Keynote on iPad is very limited, at least compared to Keynote on Mac. You can edit many style options, but only the Mac
version allows you to export them as a theme. This is a thing seen through many apps, both first and third party, where
the Mac version is significantly stronger than the iPad version, sometimes for no particular reason (and that's why
Photomator is so cool on iPad, it can do things Photos can only do on Mac).

So, I started creating the theme on Mac. I opened a presentation with the Simple White theme, and pressed cmd+shift+e to
edit the slide templates. I opened the jekyl-glass theme in a second window, and created a color swatch for its colors.
(for reference, they are #1b2f33 and white). I also added the transparent border and background colors, and also a fixed
color version of the background.

More iteration was also done on the various text fields. The "Agenda", "Quote" and "Facts" slides are unneccssary, I've
used "Fact" once, and Agenda is just Title and Bullets. However, I spent a lot of time figuring out how to put rounded
corners on a text field. The short story is: you can't. The long story is: you can't. Paragraph styles can have rounded
corners, but the radii are decided by Keynote. For the content of the Bullets slides, I first used pointed corners, but
in the end, I just put a rectangle behind the text field, and set it to be behind the text. This is a bit of a hack, but it works. [^1]

You will be able to download the theme soon, after I remove the EXIF data from the placeholder images.


[^1]: And GitHub Copilot was, again, able to complete this sentence.