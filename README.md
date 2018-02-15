# Liquid CLient 

Client side web pages with text-panes that interact with liquid-server

## Installation

To generate a tutorial from .lhs files, do the following:

```
$ mkdir tutorial
$ cd tutorial
$ git clone git@github.com:ucsd-progsys/liquid-client-retro.git
$ git clone git@github.com:ucsd-progsys/lh-workshop.git
$ stack exec -- make
```

and then view the generated documents at:

```
$ open docs/01-index.html
```

## Customizing

You can install [liquid-server](https://github.com/ucsd-progsys/liquid-server)

You can edit 

```
liquid-client-retro/assets/templates/preamble.lhs
```

to change the title etc. and the `liquidserver` 
field to point to wherever your `liquid-server` 
is running.

Once you get the above working, you can then edit the 
`lh-workshop/src/*.lhs` as you like to fill them with 
your content.

