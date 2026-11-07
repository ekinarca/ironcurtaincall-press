Play it free now: the demo on Steam (https://store.steampowered.com/app/5417460/Iron_Curtain_Call/) or 60 seconds in your browser with nothing to download (https://ironcurtaincall.com/play/).

# Iron Curtain Call: fact sheet and press kit index

Iron Curtain Call (subtitle: World War III: Third Time's the Charm) is a fast paced cartoon noir first person shooter
set in an absurd alternate 1965. You dash, grapple and parry through an army of wind up tin robots, turn enemies into
health and ammo, and bring down theatrical bosses with an arsenal of very undiplomatic weapons.

This repository holds the press kit files that are too big for the website: the trailers as 1080p MP4 files, in its
release. The press kit itself, with stills, GIFs, key art and the streamer guide, is at https://ironcurtaincall.com/press/

## At a glance

| | |
|---|---|
| Game | Iron Curtain Call |
| Genre | First person shooter, boomer shooter, comedy |
| Developer and publisher | Whale Development Studios |
| Release date | 11 March 2027 |
| Platforms | Windows and macOS |
| Free demo | On Steam now: chapter 1, "Welcome to Rubbleton" |
| Engine | Godot 4.7 |
| Weapons | 11 guns in the full game |
| Chapters | 12 |
| Price | Not set yet |
| Style | 1930s rubber hose cartoon theatre, ink lines, newsreels, a swing noir score. Robots burst into bolts, springs and scrap. No gore. |
| Voice | Every line is voiced |

## Data

The two 2027 lists the guides on ironcurtaincall.com keep, as CSV and JSON with the source, the read day and the rule: the upcoming
FPS games and the upcoming Mac shooters and action games on Steam, in [data/2027-shooters-and-mac/](data/2027-shooters-and-mac/).

## Where to play and wishlist

- Free Steam demo, chapter 1: https://store.steampowered.com/app/5451220/
- The game on Steam: https://store.steampowered.com/app/5417460/Iron_Curtain_Call/
- A 60 second trial in your browser, no download and no account: https://ironcurtaincall.com/play/
- The 1965 customer service line, a working rotary telephone in the browser (dial 1 9 6 5): https://ironcurtaincall.com/call/

The demo is a free trial of the war, and the full game is the upgrade to the full war. That is the demo's own closing
joke.

## The story

It is 1965 and year three of World War III. Humanity ran out of soldiers. The Directorate's army is made of wind up tin
robots, run by the Supreme Chancellor, a customer service engine that was handed a country. Allied Command's finest
soldier was on vacation, so they sent Corporal Punishment, who is silent and was delivered like cargo. Colonel Panic is
on the radio: "I'd send backup, but you are the backup."

### Cast

- Corporal Punishment: the player, a silent soldier delivered to the front like cargo.
- Colonel Panic: on the radio.
- The Supreme Chancellor: a customer service engine that was handed a country.
- Major Disaster: the first boss, with seventeen medals, all self awarded.
- Tin Grunts, Tick Tocks (they want a hug and are a bomb) and the Motherboard (the chapter 2 boss).

## How it plays

Punch a robot for health with the Knuckle Sandwich, open one for ammo with the Can Opener, and refill armor with the
Hot Take shoulder flamethrower. Parry the pink attacks and use the Encore super. You have a double jump, an air dash
and a grapple.

Weapons named on the Steam page: the Diplomat (shotgun), the Typewriter (submachine gun), the Care Package (rocket
launcher), the Telegram (lightning) and the Snow Globe (freezes enemies). More are shown in the arsenal cards: the Veto,
the Filibuster, the Party Line, the Lobbyist, the Pink Slip, the Whistleblower and the Bailout.

The 12 chapters: 1 Rubbleton, 2 Factory Reset, 3 Dead Air, 4 Landslide, 5 Kelvingrad, 6 Expo '65, 7 Friendly Fire,
8 Nothing to Hide, 9 Trickle Down, 10 One Small Step, 11 Please Hold, 12 Curtain Call.

## The demo

Mission 1, "Welcome to Rubbleton", takes about 15 to 20 minutes: a crashed cargo plane, the 6:15 express (a train with
teeth), the rooftops, the Hotel Majestic and the first boss, Major Disaster. Feedback from the demo goes to
contact@whaledevstudios.com.

## Browser trial and embed code

"60 Seconds of War" is a free trial of the game that runs in a current desktop or laptop browser with WebGL 2,
WebAssembly and audio worklets. It needs a keyboard and a mouse, has no touch controls, and downloads about 36 MB when
a visitor clicks play: https://ironcurtaincall.com/play/ It is also on itch.io:
https://whaledevstudios.itch.io/iron-curtain-call-60-seconds-of-war

To put the trial in your article, paste this code (also shown at https://ironcurtaincall.com/press/#embed):

```html
<iframe src="https://ironcurtaincall.com/play/embed/" title="Iron Curtain Call: 60 Seconds of War, a free browser FPS trial" style="width:960px;max-width:100%;aspect-ratio:16/9;border:0" loading="lazy" allow="fullscreen; autoplay; gamepad" allowfullscreen></iframe>
<p><a href="https://ironcurtaincall.com/play/">Iron Curtain Call: 60 Seconds of War, free in your browser</a></p>
```

## Trailers in this repository

Release [`trailers-20261009`](../../releases/tag/trailers-20261009), the cut of 9 October 2026. All four are MP4 files
at 1920 by 1080 and 30 fps, with H.264 video at about 20 Mbit/s and AAC stereo sound at 48 kHz.

| File | Trailer | Length | Size | SHA256 |
|---|---|---|---|---|
| `IronCurtainCall_StoryTrailer_EN_1080p.mp4` | Story trailer, English | 2:49 | 425,850,401 bytes (426 MB) | `f0c4fd7cefd888c2552334764a0339120cccdc9ca66b795717e8dfa535d356be` |
| `IronCurtainCall_GameplayTrailer_EN_1080p.mp4` | Gameplay trailer, English | 2:02 | 308,271,227 bytes (308 MB) | `57144b7088ea8a2927c3e02b1ea3e138441c6cef3f0bbff0900c74007a383bb1` |
| `IronCurtainCall_StoryTrailer_TR_1080p.mp4` | Story trailer, Turkish | 2:51 | 430,626,426 bytes (431 MB) | `705429b33d31f03db67f9ccea5f7127d79175ea0db9131b62364d5fe56318658` |
| `IronCurtainCall_GameplayTrailer_TR_1080p.mp4` | Gameplay trailer, Turkish | 2:05 | 315,569,421 bytes (316 MB) | `dbd041ceb7510fc84294174639cf056592f8992677454249a6484bed36c19e4c` |

The same values are in `SHA256SUMS.txt` in the release. To check a download, run `shasum -a 256 <file>` and compare.
The English story trailer is also on YouTube: https://youtu.be/N0jjU9vN0wE

Upload a trailer natively to your channel or cut it into your own video. A Steam link in the description helps.
Everything here may be used in coverage of Iron Curtain Call.

## Languages

The game's Steam page lists English, Spanish (Spain and Latin America), Arabic, Simplified Chinese, Hindi, Turkish,
Japanese and Korean. The full game is planned to get Korean, Japanese and Chinese with full voice and full text, with
no date yet.

## Guides

Plain guides to the games around Iron Curtain Call, with sources, on https://ironcurtaincall.com/guides/ (all answered
HTTP 200 on 5 November 2026).

English:

- [Best free FPS and boomer shooter demos on Steam](https://ironcurtaincall.com/guides/best-free-fps-demos-on-steam/)
- [Games like ULTRAKILL, DOOM Eternal and MULLET MADJACK](https://ironcurtaincall.com/guides/fast-paced-fps-games-like-ultrakill-and-mullet-madjack/)
- [Rubber hose FPS games like MOUSE: P.I. For Hire and Cuphead](https://ironcurtaincall.com/guides/rubber-hose-and-1930s-cartoon-fps-games/)
- [Upcoming FPS games in 2027](https://ironcurtaincall.com/guides/upcoming-fps-games-2027/)
- [Upcoming Mac games in 2027](https://ironcurtaincall.com/guides/upcoming-mac-games-2027/)

Other languages:

- German: [Neue Shooter 2027](https://ironcurtaincall.com/de/guides/neue-shooter-2027/), [Retro Cartoon Shooter](https://ironcurtaincall.com/de/guides/retro-cartoon-shooter-und-spiele-wie-cuphead-und-bioshock/)
- French: [FPS style Cuphead](https://ironcurtaincall.com/fr/guides/fps-style-cuphead-et-boomer-shooters-cartoon/), [Prochains jeux FPS de 2027](https://ironcurtaincall.com/fr/guides/nouveaux-jeux-fps-2027/)
- Japanese: [Cuphead style cartoon FPS](https://ironcurtaincall.com/ja/guides/cuphead-style-cartoon-fps-games/), [2027年のFPS新作](https://ironcurtaincall.com/ja/guides/upcoming-fps-games-2027/)
- Korean: [Cuphead style cartoon FPS](https://ironcurtaincall.com/ko/guides/cuphead-style-cartoon-fps-games/), [2027년 출시 예정 FPS](https://ironcurtaincall.com/ko/guides/upcoming-fps-games-2027/)
- Russian: [Шутеры 2027 на ПК и Mac](https://ironcurtaincall.com/ru/guides/shutery-2027-na-pk/), [Шутеры в стиле Cuphead](https://ironcurtaincall.com/ru/guides/shutery-v-stile-cuphead-i-rubber-hose-fps/)
- Chinese: [类似茶杯头的游戏](https://ironcurtaincall.com/zh/guides/cuphead-style-rubber-hose-cartoon-fps/), [2027年新游戏](https://ironcurtaincall.com/zh/guides/upcoming-fps-games-2027/)

## Made with, and the AI disclosure

The game is built in Godot 4.7. The disclosure also stands on the Steam page and in the game's credits.

The code was written with AI coding agents that the founder directed and tested every day. The levels, the weapon feel,
the pacing and every design decision were made by hand, and the hardest month of the project was level design. The
voices were generated with ElevenLabs from lines the founder wrote and directed. Some art used Higgsfield, and the score
was synthesised with FluidSynth plus a few ElevenLabs Music cues. No artist's work was copied and no voice actor was
imitated.

The game's music is safe to use on streams and videos.

## The studio and contact

Whale Development Studios is an independent game studio. Website: https://whaledevstudios.com

Press, interviews and questions: contact@whaledevstudios.com

Iron Curtain Call and WW3: Third Time's the Charm are works of satire. Any resemblance to real wars, committees or
customer service lines is entirely intentional.

© 2026 Whale Development Studios.
