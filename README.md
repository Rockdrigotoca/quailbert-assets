# Quailbert assets

Pictures for Sir Quailbert the Wanderer (the Quailwood Club Discord bot). They are served by GitHub Pages, so Discord can show them by link:

`https://rockdrigotoca.github.io/quailbert-assets/<folder>/<file>`

## How to add a picture
1. Name it in lower case with dashes, no spaces, for example `toss-heads.png`.
2. PNG or WebP, ideally under 500 KB (hard limit 1 MB). Square images, 512 to 1024 px, look best in Discord.
3. Drop it in the folder below (on github.com: open the folder, **Add file** → **Upload files**, then **Commit changes**).
4. Tell Sir Quailbert's builder, who wires it up.

## Folders and what they hold

### fun/ (coin toss and other flavour)
| File | Used for | Status |
| --- | --- | --- |
| `toss-heads.png` | `/toss`, heads | have it |
| `toss-tails.png` | `/toss`, tails | have it |
| `toss-side.png` | `/toss`, lands on its side | have it |
| `toss-drunk.png` | `/toss` while Sir Quailbert is drunk | have it |
| `duel.png` | `/duel` banner | needed |
| `curse.png` | `/curse` banner | needed |
| `feast.png` | `/feast` banner | needed |
| `drunk.png` | `/drink` result, Sir Quailbert tipsy | needed |
| `sober.png` | `/drink` or `/soberup`, Sir Quailbert sobering up | needed |
| `talk-1.png` … `talk-5.png` | `/talk` moods (cheerful, grumpy, mystical, sleepy, scheming) | needed, optional |

### system/
| File | Used for | Status |
| --- | --- | --- |
| `image-not-found.png` | when a picture is missing | have it |
| `admins-only.png` | "this is for the council" refusal | have it |
| `avatar.png` | bot avatar for the server | needed (the Developer Portal already has one) |
| `menu.png` | banner on `/menu` (the main menu) | needed |
| `help.png` | banner on `/help` | needed |

### map/
Pictures of Quailwood locations for `/map_of_quailwood`. The old bot kept one test entry, so everything here is new. One image per location, named after it, for example `town-square.png`. A list of the locations to illustrate comes with the map port.

### trains/
Spark trains. Nomentano first (Count Nomento's voice). Pictures marked "per voice" need a `-count` version (Nomentano) and later a `-quailbert` version (Quailwood and other servers). Square thumbnails 256 to 512 px; the wide pictures about 1024 x 512 px (2:1). Save the train pictures as JPG (the bot looks for `.jpg`), under 1 MB.

**Nomentano set (needed first)**
| File | Shape | Used for | Status |
| --- | --- | --- | --- |
| `spin-count.jpg` | wide | the Count spinning the wheel of names; shown when the next round's order is drawn and on `/train spin` | have it |
| `train-5.jpg` | portrait | thumbnail on the 5-spark train's cards | have it |
| `train-3.jpg` | portrait | thumbnail on the 3-spark train's cards | have it |
| `train-1.jpg` | portrait | thumbnail on the 1-spark train's cards | have it |
| `next-up-count.jpg` | square | thumbnail on "Next build" (the next builder's address announcement) | needed |
| `train-done-count.jpg` | wide | when a train is ended with `/train end` | needed |

**Later (Quailwood and other servers)**
| File | Shape | Used for | Status |
| --- | --- | --- | --- |
| `spin-quailbert.jpg` | wide | Sir Quailbert spinning the wheel | needed |
| `next-up-quailbert.jpg` | square | "Next build" with Sir Quailbert | needed |
| `train-done-quailbert.jpg` | wide | end of a train with Sir Quailbert | needed |
| `train-2.jpg`, `train-4.jpg` | square | the Quailwood 2- and 4-spark trains | needed |

If a picture is missing, the message simply shows without it.

### seasons/
| File | Used for | Status |
| --- | --- | --- |
| `pulse.png` | banner for the Monday Quailwood post | needed |
| `watch.png` | banner for the seasonal score tracker (residents and influence) | needed |
