TIMER
=====

A countdown timer application written in javascript powered by django and deployed to heroku that notifies you via email that the countdown timer set has been stopped.


TODO
====

* Automate sending of mail as and when timer stops.


ISSUES
======

* Accomodate for different time zones. ( App opened in different time zones show different countdown time)

### Solution -

Try running this app as a cron job on our own server.( This is one of the solution)


Stretch Goal
============

* Integrate twilio to enable SMS to the users registered.
