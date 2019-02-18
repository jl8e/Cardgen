# Cardgen
Custom card generator written in python, outputting to HTML/CSS

Having just helped in the production of a LARP again, I feel that there should be a better way of making
cards than the tools we were using. When we did Ghost Fu, we generated the cards in HTML from a spreadheet
with a Perl script. It was awful. I want to recreate that, with more flexibility, and hopefully the improvements
in CSS support over the past decade will make to more painless. Also in Python, speaking of reduced pain.

Why not do it as a web app in Javascript? Because I hate Javascript, and nobody's paying me to do this.
(I'll still likely need to use some JS to check for box overflow.)

The basic workflow will be:

- Write a config file telling it what columbs in your spreadsheet go where, and similar things
- Save spreadsheet as cvs
- run scrit with config and spreadsheet
- look at generated html files
- curse
- iterate

In later versions, it may be worth having a web interface (yes, JS. *spits*), but not for now.
