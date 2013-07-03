autoappupdate
=============

## What: ##

A collection of scripts to automatically install/update Mac OS X apps/prefPanes/Java/Flash/etc but only if a newer version is available.


## Why: ##

After making [au-xld] I realized that this was something I would want to replicate for several apps. In my 10 years as a Mac user I have accumulated 5 Macs. While I primarily use my MacBook Air, I so want to be able to keep the others up to date.

I needed a process that I could automate so that it can run unattended between 2:00 a.m. and 7:00 a.m. when my satellite Internet connection is not restricted.

Although it is very handy to have apps which can update themselves, I've always found it distracting to have an alert pop-up and say "Do you want to update this app?" 99 times out of 100 the answer is "Yes, but not right now, I'm busy" so I click the "Remind Me Later" button, which also inevitably comes up at an inconvenient time.

How much nicer would it be to sit down at the computer in the morning and see a few notifications of any applications which had been automatically updated overnight?

## Naming Convention ##

The scripts will be named "au-*APPNAME*.sh" where "au" stands for "auto-update" and *APPNAME* is the actual name of the app, e.g. `au-dropbox.sh`

## This won't satisfy everyone ##

[homebrew-cask] is probably a much better solution than what I have made here. These scripts just meant to scratch my particular itch, and I thought it might be helpful to someone else, or perhaps just give them an idea of how they might solve a problem.

## See Also: ##

If you are thinking of using any of these scripts you should start by reading [au-TEMPLATE.mmd] which gives an overview of how the scripts work as well as "guiding principles" behind the project.


[au-TEMPLATE.mmd]: https://github.com/tjluoma/autoappupdate/blob/master/au-TEMPLATE.mmd




[homebrew-cask]: https://github.com/phinze/homebrew-cask
[au-xld]: https://github.com/tjluoma/au-xld

