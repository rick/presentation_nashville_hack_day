!SLIDE

# Lemme go fix this

!SLIDE

# Lemme go fix this

### or, how do we improve software
### that we don't know?

!SLIDE

## Rick Bradley
### rick@rickbradley.com
### @rickbradley

!SLIDE

### formerly of O.G. Consulting
### nowly of the Git Hubs

!SLIDE

# Software in the Small

!SLIDE

## This thing I use
## needs fixing


!SLIDE

## By "needs fixing"
## I mean I have a certain goal

!SLIDE

## Bugfix to functionality

!SLIDE

## Feature addition
## to support MY needs

!SLIDE

## The documentation is jank

!SLIDE

## I love the project
##  So I'm just hitting
##  Their issue reports for them

!SLIDE

## In all of these cases

!SLIDE

## There is some *NEED* driving my work

!SLIDE

# NEED-Driven Development

!SLIDE

# (NDD)

!SLIDE

# First Rule:

# Stick To The *Need*


!SLIDE

### Differentiate between
### experimentation for discovery
### and *work* on the system
### towards some goal


!SLIDE

### Code written experimentally
### is a *spike*

!SLIDE

### Code written towards a goal
### carries higher standards
### and is *not* a spike

!SLIDE

## Know when you are doing which

!SLIDE

## Learn from your spikes
## and throw them away

!SLIDE

## Then write your
## *real* code

!SLIDE

# How to approach
# the unknown
# code base

!SLIDE

## Small jobs don't get an audit

!SLIDE

## But...
## improve the code
## improve the tests
## improve the docs

!SLIDE

## No tests?

## Make the first tests
## for the high-level stuff
## related to your *NEED*

!SLIDE

## Weak tests?

## Add tests
## for the high-level stuff
## related to your *NEED*

!SLIDE

## Good tests?

## Add and refactor tests
## for the detailed stuff
## related to your *NEED*

!SLIDE

## When you make changes
### Find all the callers
### Find all the tests
### Find all the docs

## ... and *improve them*

!SLIDE

## Leave it better
## than you found it

!SLIDE

# Software in the Large

!SLIDE

## Everything before is still true

!SLIDE

## BUT

!SLIDE

## All your problems are social now.

!SLIDE

## Do an audit


!SLIDE

## Do an audit
### (bonus points if someone will pay you for it)

!SLIDE

## To improve the project
## You will need to do technical things
## addressing a real *NEED*

!SLIDE

## So you need to do the right
## technical things

!SLIDE

## In such a way that
## you slowly uncover
## the social problems
## that account for the weirdness
## in the software

!SLIDE

# Audit

!SLIDE

## Use automated tools

!SLIDE

### (ruby-world, please translate...)

## flog
## rcov
## churn
## metric-fu
## etc.

!SLIDE

## switch over to eyeballs
## and ad hoc tools

!SLIDE

### open up in a code editor with a drawer
### find . | xargs wc -l | sort -n
### (open up big files)
### (read the code of files with high churn)
### git blame
### *read the codes*

!SLIDE

### read bug reports
### read version control history
### read mailing list backlogs
### ask questions of domain experts
### "so, is *somedude* still here?"

!SLIDE

### write up an audit doc
### even if it's just for yourself
### problem areas
### domain refactoring guesses
### places that could use better tests

!SLIDE

## Dig In

!SLIDE

## Tackle a problem area that is small
### but important
### known
### and causing headaches

!SLIDE

## Do NDD
### Spike
### un-spike
### Improve *ALL THE THINGS*
### use version control Like A Boss
### Be very careful
### and deploy a Win

!SLIDE

## Pick another
### and repeat

!SLIDE

### but each time,
### try to figure out
### why this wasn't fixed before

!SLIDE

### be nice
### maybe be quiet
### ask questions that carry possible answers

!SLIDE

### "So, was this paired on?"

!SLIDE

### "I notice that it was hard to deploy -- is that automated?"

!SLIDE

### "I'm trying to stay on a branch for as short a time as possible, are there a lot of long branches?"

!SLIDE

### "Oh I see ... could we avoid that in the future by ...?"

!SLIDE

## Don't Care

!SLIDE

## At the end of the day
## you likely can't solve the social problems,
## so do what you can
## and let it roll.

!SLIDE

## Picking a fight
## just slows things down
## and doesn't get the problem solved

!SLIDE

## Let people on the team
## run with the ball
## when a good idea comes out

!SLIDE

## When progress starts to happen
## it starts to happen faster
## and if there are managers,
## progress makes them better managers

!SLIDE

## That is,
## it makes them leave people alone.

!SLIDE

## After all,
## no manager is better
## than

!SLIDE

## no manager.

!SLIDE
# Thanks
