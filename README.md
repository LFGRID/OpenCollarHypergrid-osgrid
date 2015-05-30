### OpenCollar Hypergrid

This an attempt to port OpenCollar to OpenSim, where we want to try to:

1. Create a source that hosts things in common for all OpenSim grids.

2. Create dedicated branches for individual grids to fine tune things.

#### Critical Scope:

Will be the core, which are:

- auth
- settings
- dialog
- listener
- main

#### Primary Scope:

Will be the features we expect in a collar the most:

- leash
- anim
- couples
- hide
- rlv

#### Secondary Scope:

Will be visual customization and specialty plugins:

- appearance
- texture
- color
- badwords
- etc..

#### What else?

This is separate from the OpenCollarUpdater repo to encourage a more active development. Many people expressed concerns they could mess things up because of not being very familiar with git version control. This should never be a worry, nobody will chide or scold anyone if mistakes happen and it's version control after all, we can roll back and forth and generally wallow in our source like a bunch of merry piglets on a roll! Yay! (Did I seriously just write that...) Anyway, collaborators from various grids will receive write access as "Team Hypergrid" and can organize things on the provided issue tracker.

#### Animations, textures, models and sounds:

For now, please just use a torus shaped prim with... another torus shaped prim for a ring and.. oh well, maybe use a blank texture and make it shiny. In the not so far future, we are going to release a 3D model with texture maps, split up in several elements that everyone can upload without having to worry about licensing issues in elements used from the Second Life grid. That's right, many collar designs use textures or sculpt maps that we can't just as easily move from here to there.

Animations have the same constraint, what we have right now on the Second Life grid are motions we cannot export without taking the risk to violate licenses. What we have in place are height-scalar animations and a basic hug [here](https://github.com/OpenCollar/OpenCollarAnimations).

The init of this source is based on the 3.990 public release from the Second Life grid. Our master branch here is called "hypergrid".