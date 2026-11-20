# Cut the Country

A daily browser game: every day, one country to cut into two pieces of equal area, with a single straight line.

**Play:** https://yourusername.github.io/coupe-le-pays/

## How it works

Today's country appears on an old explorer's chart. You place a first point, then a second one on the other side: the line runs from edge to edge, a small plane flies the route across the map, and the map tears in two along it. The goal is to get as close as possible to a 50 / 50 split.

Only one cut counts per day. Every player gets the same country, and a new one arrives every day at midnight.

| Medal | Rating | Gap from 50 / 50 |
|-------|--------|------------------|
| 🏆 Trophy | Perfect | less than 0.25 points |
| 🥇 Gold | Excellent | less than 1 point |
| 🥈 Silver | Well done | less than 2.5 points |
| 🥉 Bronze | Not bad | less than 5 points |
| No medal | Missed | 5 points or more |

## Features

- **Today's country**: one cut per day, with a result you can share without revealing the country (the medal emoji and the two shares).
- **Practice**: random countries, as many as you like. After a cut, a click or tap on an empty part of the map moves on to another country.
- **Medals**: the medal drops in next to the verdict with a small metallic clink. The statistics show your medal count, and the help shows the scale.
- **Statistics**: days played, average gap, best gap, current streak, and the medal count.
- **Throwing the pieces**: once the result is shown, grab either half of the country with the mouse or a finger and throw it anywhere in the window. Pieces fall, spin, bounce off the window edges and off each other.
  - A hard knock tears a piece in two along a ragged line, with a few paper crumbs; a very hard one breaks it again. A piece simply dropped lands whole.
  - Nothing breaks over the map, and a piece that has left the map cannot come back in, so the playing area stays clear.
  - Broken bits disappear 2.5 seconds after breaking, fading and shrinking in the last 0.6 seconds. Picking one up pauses its countdown, which restarts when you let go. Whole pieces fade after 6 seconds without moving.
- **Mouse**: two clicks, or a drag from one side to the other. Esc or right-click cancels before the second click.
- **Touch**: tap two points (or swipe across). The line then waits: drag a point to adjust it, drag elsewhere on the map to move the whole line, or use two fingers to move both points at once. The cut only happens when you tap "Cut here". This button only appears on phones and tablets.
- **Country flag** next to the country name, drawn in the page so it also shows on Windows.
- **Sound**, generated in the browser: a propeller plane crossing the map and paper tearing on every cut, a short tune that depends on your rating (brass and timpani for a perfect cut, a rolling boulder for a miss), and thuds, whooshes and cracks when you throw the pieces. The speaker button or the M key mutes it.
- **Accessibility**: menus work with the keyboard, medals are told apart by shape and name as well as colour, and animations are reduced when the system asks for it.

## Languages

The game is available in 13 languages, with English as the default: English, Français, Español, Deutsch, Italiano, Português, Nederlands, Polski, Türkçe, Русский, 日本語, 한국어 and 简体中文. The flag button next to the sound button opens the list. The choice is saved in the browser, and country names, numbers and the share text follow the selected language.

## How areas are measured

Each country is drawn with a Lambert azimuthal equal-area projection centred on the country. This projection preserves areas: the proportions on screen match the real surfaces, even for large countries such as Russia or Canada.

Small, remote territories (overseas islands, distant archipelagos) are left out to keep the shape playable.

## Made with AI

This game was vibe coded: I described what I wanted, played each version and asked for changes, and an AI assistant ([Claude](https://claude.ai), by Anthropic) wrote the code, the visuals, the sounds and the translations. The ideas, the choices and the testing are mine; the code is the AI's.
