# Heroku CLI snap

This project creates a working snap for Heroku's CLI.
Heroku is migrating it's CLI to go, so this project is evoling rapidly. Getting
it packaged in a snap and installable in Ubuntu from edge, beta and stable
channels sounds really cool.

## Current state

Working features:
 - login, in devmode

Known issues:
 - without devmode, it gets stuck.
   Reported in https://bugs.launchpad.net/snappy/+bug/1590221

Unknowns:
 - it has an update command, that self-updates. I'm not sure how that will work
   in the snappy world. Should it be patched to call snap refresh?
