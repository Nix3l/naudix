# Naudix
naudix is a discord music or audio bot made by me. it is made entirely in java using the java discord api (jda) library
this is entirely free and open source

## Features
naudix currently can:

1. load songs from spotify and youtube
2. search youtube for videos and loading the top one
3. a functional queue
4. it has volume control

## Limitations
the only real limitation is that it only works in one server at a time.
I never bothered to set up database compatibility in order to support multiple servers since i wasnt exactly that commited.
Plus i never really planned to use it since it was just a project i started.

## Why did i start making it?
idk. woke up one day and i was like "you know what would be fun? making a discord music bot" and thus spent the next week working on it

## Will i ever finish it?
idk maybe. if someone wants me to then sure

## Can i yoink the source code?
as long as you abide by the gplv3 license (i.e. you have to keep your code open source too), then yes.
and it would be nice if you credited me somewhere too

## this code is awful dude you suck
ik the code isnt the neatest thing in the world in some places but eh i didnt make this with the intention of making the best code.
i just wanted to get a working prototype up.

## NOTES for myself later on if i come back to the project
1. add proper yt api support instead of the bs im doing now to avoid it
2. make my own implementation of the queue that isnt FIFO so i can fetch certain elements in the middle allowing for removing of songs from the queue
3. add per-server queue and audio managing support
4. make text feedback look nicer
5. maybe utilize asynchronous code for loading songs
