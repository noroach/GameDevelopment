# JustMakeAGameAlready
Author: Nolan Roach

This repo is for personal programming and game projects that I will be working on over the course of the year.
If you are viewing this, then you must be a friend, employer or person who wishes to view/test/play something
that I've created. Hopefully something in here will peak your interest or impress you in some fashion.








This is a just description of the gitignore that people use for development in Unity:

The most popular hit for “unity gitignore” is a post on the official Unity forums that was written by someone who doesn’t seem to fully understand how git works. Which was a little disappointing.

Before you commit anything to git, you MUST go into Unity’s menus and enable the “metadata” option (in settings, moves around a bit between versions). Without that, Unity’s internal data-bugs will corrupt your project if you ever merge (happens to us approx 1 time in 3 if we forget at start of project)

After a bit of trial and error, here’s a basic .gitignore for Unity that seems to work, and cut down the commit sizes by a factor of 4 immediately:

UPDATE: updated with a tried-and-tested gitignore that covers more things. Do please note the big WARNING though, or you’ll only have yourself to blame…
