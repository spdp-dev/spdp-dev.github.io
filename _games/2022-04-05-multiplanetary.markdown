---
layout: game

title: Multiplanetary
release_year: 2022
abstract: Billionaires are leaving. Send them back!
made_for: Made for Ludum Dare.
thumb: /assets/img/multiplanetary-thumb.png
thumb_alt: Multiplanetary gameplay thumbnail.
credit:
  name: Stephen Pearce
# team:
#   - name: Stephen Pearce
#     url:  https://spdp.dev
platforms:
  - name: Itch.io
    url: https://spdp.itch.io/multiplanetary
created: 2022-04-05 06:30:49 +0100
#updated: 
tags: ["Game Jam"]
is_game: true
---

| Made with | Unity |
| Timeline | 72 hours |
| Playable | <a href="https://spdp.itch.io/multiplanetary" rel="nofollow noopener noreferrer" target="_blank" title="Play it on Itch.io">Itch.io</a> |


## Retrospective
Made for <a href="https://ldjam.com/events/ludum-dare/50" rel="nofollow noopener noreferrer" target="_blank">Ludum Dare 50</a> with the theme "delay the inevitable".


### The Idea
Unlike other jams I&apos;ve participated in, LD&apos;s community voting rounds meant that I had an idea for what the theme might be ahead of time. I was able to generate a bunch of ideas on many sheets of A4 the night prior. The first of those ideas is what I took forward into the jam.

With the theme "delay the inevitable", I settled on the idea that humanity will inevitably become a multiplanetary species and that you would be in control of an alien device trying to prevent it. Shuttles would spawn at random intervals from Earth and head in the direction of neighbouring planets. The player would be facing Earth and only able to move within a certain range of it&apos;s orbit.


### What Went Well
I had a few things to learn in order to make my idea work. These aspects at least went well.

* Spawning prefabs at particular rotations
* Circular motion around a fixed point with boundaries
* 9-slice / 9-patch scalable sprites for the menu buttons - my buttons no longer jank at different scales!
* Preventing accidental triggering of menu items when switching scenes.
* I made an attempt at hand drawing some art with a tablet, but pulled it at the last minute as I felt I wouldn&apos;t be able to change everything within the remaining hours. I was only able to roll back because I had everything in Git and mirrored to GitHub. Version control FTW!


### What Went Wrong
* I wasted the better part of two days on project plumbing and menu code. You don&apos;t need either in a game jam.
* I don&apos;t like to blame the tools...but the tools crashed a lot on me this weekend. Ordinarily this wouldn&apos;t bother me, but when you&apos;re strapped for time then it really adds to the pressure.
* I should&apos;ve playtested. It became clear after submitting that the game is much too difficult and it&apos;s suffering in the feedback as a result.
* The game was made with a game controller in mind...but you can&apos;t assume that the folks playing will be using such hardware. The keyboard experience doesn&apos;t quite match the controller and as such the game is much more difficult on a keyboard than it ought to be.
* I completely forgot that difficulty should scale. My game appears to be backward in that sense in that it&apos;s actually most difficult upfront then gets slightly easier as time progresses, assuming RNG in is the player&apos;s favour. Playtesting the game even a couple of hours before submission would&apos;ve caught this.


### What I Learned
It&apos;s been nine months since I last attempted a game jam so I&apos;ve definitely had to remind myself of the standard practices.

I happened upon <a href="https://www.youtube.com/watch?v=lPyYZjCQ0Is" rel="nofollow noopener noreferrer" target="_blank">the 4:44 rule</a> whilst testing other&apos;s submissions, and I think I'll apply it when the next game jam opportunity rolls around.