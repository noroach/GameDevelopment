# JustMakeAGameAlready
Game Project

The most popular hit for “unity gitignore” is a post on the official Unity forums that was written by someone who doesn’t seem to fully understand how git works. Which was a little disappointing.

Before you commit anything to git, you MUST go into Unity’s menus and enable the “metadata” option (in settings, moves around a bit between versions). Without that, Unity’s internal data-bugs will corrupt your project if you ever merge (happens to us approx 1 time in 3 if we forget at start of project)

After a bit of trial and error, here’s a basic .gitignore for Unity that seems to work, and cut down the commit sizes by a factor of 4 immediately:

UPDATE: updated with a tried-and-tested gitignore that covers more things. Do please note the big WARNING though, or you’ll only have yourself to blame…
