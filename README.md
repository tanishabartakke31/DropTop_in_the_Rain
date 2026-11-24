# drop top in the rain

**play it here → https://drop-top-in-the-rain-wdv5.vercel.app**

you know that thing you did as a kid, sitting by a window when it rained,
picking one drop and watching it race the others to the bottom?

this is that.

## how it works

- tap a drop on the glass. that one's yours.
- they all start sliding down. some get stuck for a bit, some take off.
- first one to the bottom wins.
- if a bigger drop runs into yours, it swallows it and you lose. it's not fair.
  rain isn't fair.

## difficulty

| mode | drops | speed |
| --- | --- | --- |
| easy | 6 | slower |
| normal | 9 | normal |
| hard | 13 | faster |

more drops means more chances for yours to get eaten.

## other stuff

- **night mode** (the ☾ button): the sky goes dark, lit windows flicker in
  the distance, and every now and then there's lightning and thunder
- **sound**: rain, little clicks, a win/lose jingle. all of it is generated
  in the browser, there are no audio files. 🔊 mutes it
- **best time** is saved, so it's still there after you refresh
- **win streak** isn't saved. refresh and it's gone
- works on phones too, just tap

## running it

easiest way is the link up top. it's hosted on vercel.

to run it locally: it's one html file. no install, no build, no dependencies.

```bash
git clone https://github.com/tanishabartakke31/drop-top-in-the-rain.git
cd drop-top-in-the-rain
open index.html
```

or just double click `index.html`.

## built with

plain html, css and javascript. the drops, the sky, the splashes are all drawn
on a `<canvas>`, and the sound uses the Web Audio API.

## things i might add

- keep the streak after a refresh
- a leaderboard
- betting on two drops at once

made by tanisha.
