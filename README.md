# 🏄‍♀️ Surf Me to the Moon 🌙

![GameMaker](https://img.shields.io/badge/GameMaker-GML-8A2BE2?logo=gamemaker&logoColor=white)
![Language](https://img.shields.io/badge/language-GML-5C4EE5)
![Platform](https://img.shields.io/badge/platform-HTML5-1f6feb)
![Genre](https://img.shields.io/badge/genre-Platformer%20%2F%20Runner-ff69b4)
![Status](https://img.shields.io/badge/status-Released-success)
[![Play on itch.io](https://img.shields.io/badge/%E2%96%B6%20Play-itch.io-FA5C5C?logo=itchdotio&logoColor=white)](https://nachodeveloper.itch.io/surf-me-to-the-moon)

A side-scrolling **surf runner** built in **GameMaker (GML)** and released on **itch.io** for **HTML5**. Made as a **birthday gift** for **Luna Rurine**, a vtuber from the agency **Wactor**.

> 🎂 A community birthday project for Luna — part of a series of fan games I made for her and other vtubers.

**▶️ Play it:** https://nachodeveloper.itch.io/surf-me-to-the-moon

---

## About the game

Luna surfs across the sea toward the moon. Move her up and down to ride the waves, dodge incoming rocks, and scoop up *lomitos* along the way. A short, charming arcade runner made to celebrate Luna's birthday.

- **Controls:** Up/Down arrow keys or **W / S** to move Luna vertically.
- **Avoid:** rocks (`objRoca`) coming across the screen.
- **Collect:** lomitos (`objLomito`).
- **Extras:** an intro cinematic, animated background waves, dynamic background music, and a credits screen.

---

## My role

**Solo developer & project director.**

I programmed the entire game in GML and directed the production, coordinating a small creative team:

| Role | People |
|---|---|
| 🎮 Development & direction | **NachoDev** (me) |
| ✔️ Production | Ofeb Kouki |
| 🎨 Art | MelonPan |
| 🎵 Music | GerX |

---

## Technical highlights

Written in **GML** across ~60 object event scripts:

- **Vertical player movement** with wave-riding feel (`objluna/Step_0.gml`) and collision handlers for rocks and collectibles.
- **Obstacle & collectible spawning** driven by timed alarms (`objgame/Alarm_0.gml`).
- **Intro cinematic** (`objcinematic`) and animated parallax waves (`objolaback`) for presentation.
- **Dynamic background music** (`objmusica`) and a credits sequence (`objcreditos`).
- Menu / restart / info button objects for full screen flow.

**Engine:** GameMaker · **Language:** GML · **Target:** HTML5

---

## Credits & licensing

The **code** in this repository was written by me (NachoDev) and is shared for portfolio and educational purposes.

⚠️ **The art, music, and the Luna Rurine character are the property of their respective creators** (credited above) and are **not** covered by any open-source license. They are included only to make the game buildable and should not be reused without the creators' permission.

---

## Author

**Sergio Ignacio Saborío Segura** — "NachoDev"
Solo developer & director · Informatics Engineer
🎮 itch.io: https://nachodeveloper.itch.io/surf-me-to-the-moon
