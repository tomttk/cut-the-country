# Cut the Country

A daily browser game: every day, one country to cut into two pieces of equal area, with a single straight line.

## How it works

Today's country appears as a paper cut-out on a cutting mat. You place a first point, then a second one on the other side: the line runs from edge to edge and cuts the country in two. The goal is to get as close as possible to a 50 / 50 split.

Only one cut counts per day. Every player gets the same country, and a new one arrives every day at midnight.

| Rating | Gap from 50 / 50 |
|--------|------------------|
| 🎯 Perfect | less than 0.25 points |
| 🟩 Excellent | less than 1 point |
| 🟨 Well done | less than 2.5 points |
| 🟧 Not bad | less than 5 points |
| 🟥 Missed | 5 points or more |

## Features

- **Today's country**: one cut per day, with a result you can share without revealing the country.
- **Practice**: random countries, as many as you like.
- **Statistics**: days played, average gap, best gap, current streak.
- **Mouse**: two clicks, or a drag from one side to the other. Esc or right-click cancels before the second click.
- **Touch**: tap two points (or swipe across). The line then waits: drag a point to adjust it, drag elsewhere on the mat to move the whole line, or use two fingers to move both points at once. The cut only happens when you tap "Cut here".
- **Sound**: a blade sound on every cut and a short tune that depends on your rating, generated in the browser. The speaker button or the M key mutes it.
- **Accessibility**: menus work with the keyboard, and animations are reduced when the system asks for it.

## How areas are measured

Each country is drawn with a Lambert azimuthal equal-area projection centred on the country. This projection preserves areas: the proportions on screen match the real surfaces, even for large countries such as Russia or Canada.

Small, remote territories (overseas islands, distant archipelagos) are left out to keep the shape playable.