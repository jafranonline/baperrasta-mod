<div align="center">

# ⚡ বঙ্গবল্টু Mode

### God mode for [বাপের রাস্তা](https://baperrasta.com): full battery, crazy speed, and nothing can kill you

**বঙ্গবল্টু মরেনাই 💪**

[**⬇️ Install the mod**](#-install-in-3-steps) · [🎮 Controls](#-controls) · [❓ Help](#-help)

<img src="docs/hero.jpg" alt="A bus hits the rickshaw and the mod shows the বঙ্গবল্টু মরেনাই banner" width="820">

</div>

---

## 🎬 See it in action

<div align="center">
<img src="docs/gameplay.gif" alt="Driving through Dhaka at 3x speed with the battery locked at 100%" width="640">
</div>

## ✨ What you get

| | |
|---|---|
| 🔋 **Battery always 100%** | Never runs out, never drops into pedal mode |
| 💥 **Crash for free** | Hitting cars, bikes and walls costs no battery |
| ⚡ **Speed boost** | 3× speed by default; change it live with `[` and `]` |
| 🚀 **Fly Mode** | Hold `F` to fly forward above traffic, barriers and holes; release `F` to land back on the road |
| 🚌 **Bus & hole-proof** | Buses, trucks, potholes and open manholes can't kill you, and ramming buses/trucks pays ৳ like any other crash: **বঙ্গবল্টু মরেনাই!** |
| 🤑 **10× ৳** | Every crash, near miss and jump pays 10 times more |
| 🏃 **Mob-proof** | The angry crowd can't catch you or slow you down |
| 💰 **Keep your money** | Paying police "চা-পানি" doesn't cut your ৳ score |
| 🎵 **Sounds** | A clip plays when you survive a hit and when you end a run |
| ⏸️ **Pause** | Pause button under the sound button, or press `P` |
| 🏆 **Leaderboard sync** | Live background score sync and instant submission to the "মোস্ট ওয়ান্টেড" leaderboard |

<div align="center">
<img src="docs/driving.jpg" alt="In-game view with the battery at 100% and the mod's controls shown" width="820">
</div>

---

## 📥 Install in 3 steps

It takes about a minute. You do this once, and updates arrive automatically after that.

### Step 1: Get a userscript manager

This free browser extension runs the mod for you. Pick the one for your browser:

| Your browser | Install this |
|---|---|
| 🦊 **Firefox** (PC or Android) | [**Violentmonkey**](https://addons.mozilla.org/firefox/addon/violentmonkey/) |
| 🌐 **Chrome / Brave / Edge** | [**Tampermonkey**](https://www.tampermonkey.net/) |
| 🧭 **Safari** (Mac / iPhone) | [**Userscripts**](https://apps.apple.com/app/userscripts/id1463298887) |

<img src="docs/step1-manager.png" alt="Pick a userscript manager for your browser" width="720">

> [!IMPORTANT]
> **Chrome, Brave and Edge users need one extra step.** Open `chrome://extensions` (or `edge://extensions`), click **Details** under Tampermonkey and switch on **Allow User Scripts**. On older browser versions, turn on **Developer mode** at the top right instead.
>
> <img src="docs/step1b-allow-user-scripts.png" alt="Turn on Allow User Scripts in the extension details" width="640">

### Step 2: Install the mod

<div align="center">

### [👉 Click here to install `baperrasta-mod.user.js`](https://raw.githubusercontent.com/jafranonline/baperrasta-mod/main/baperrasta-mod.user.js)

</div>

Your userscript manager opens an install page. Click **Install**.

<img src="docs/step2-install.png" alt="The userscript install page with the Install button" width="720">

> **iPhone / Safari:** open the link in Safari, tap the **Userscripts** icon in the address bar, then tap **Install**.

### Step 3: Play

Open **[baperrasta.com](https://baperrasta.com)**. If it was already open, reload the page. A yellow **⚡ Bongobondhu Mode** badge under the title means the mod is working. 🎉

<img src="docs/step3-badge.jpg" alt="The game menu with the Bongobondhu Mode badge" width="820">

---

## 🎮 Controls

The normal game keys still work. The mod adds these:

<img src="docs/keys.png" alt="Mod keys: [ ] speed, Z calm mob, Shift+Z auto-calm, K or Esc end run, M sound" width="720">

| Key | What it does |
|:---:|---|
| `F` (hold) | Fly forward at limited height over traffic & holes (steer with `A`/`D` or arrows); release `F` to land |
| `]` / `[` | Speed up / slow down (0.5× steps, from 0.5× to 8×) |
| `Z` | Calm the mob right now |
| `Shift` + `Z` | Auto-calm the mob on/off |
| `P` | Pause / resume (or tap the ⏸ button) |
| `K` or `Esc` | End the run and see your ৳ score in the newspaper |
| `M` | Game sound on/off (the mod's sounds follow it) |

Because nothing can kill you, a run only ends when **you** end it. Press `K` to get the front page:

<div align="center">
<img src="docs/newspaper.jpg" alt="The end-of-run newspaper showing the score" width="820">
</div>

---

## ⚙️ Settings

Open your userscript manager → click the mod → **Edit**. The settings are at the top, in `CFG`:

```js
battery100: true,     // battery always full
speedMult: 3.0,       // starting speed (1.0 = normal)
noBusDeath: true,     // buses can't kill you
invincible: true,     // the mob can't catch you
keepMoney: true,      // police bribes are free
busPoints: true,      // ramming buses/trucks pays ৳
savedSound: true,     // sound when you survive a hit
endSound: true,       // sound when you end a run
```

Change a value, save, and reload the game.

## 🔄 Update · pause · remove

| I want to… | Do this |
|---|---|
| **Update** | Nothing to do: updates install automatically. For an update right now, open the manager's dashboard and click **Check for updates** |
| **Play normally for a while** | Switch the mod **off** in the manager, then reload the game |
| **Remove it** | Delete the mod from the manager's dashboard |

## ❓ Help

<details>
<summary><b>I don't see the ⚡ Bongobondhu Mode badge</b></summary>

1. Reload the game page. The mod has to load before the game does.
2. Check that the mod is switched **on** in your userscript manager.
3. On Chrome / Brave / Edge, make sure **Allow User Scripts** is on (see Step 1).
4. Check that the address starts with `https://baperrasta.com`.

</details>

<details>
<summary><b>The sounds don't play</b></summary>

Turn on the game's sound (the speaker button or `M`). Browsers block sound until you've clicked or pressed a key on the page once.

</details>

<details>
<summary><b>How do I submit my score to the leaderboard?</b></summary>

Your personal best and leaderboard score are synced automatically in the background while you play. Press `K` or `Esc` whenever you want to end the run, open the newspaper, and set or update your name on the "মোস্ট ওয়ান্টেড" board.

</details>

<details>
<summary><b>Does it work on Android?</b></summary>

Yes, in **Firefox for Android** with Violentmonkey. Chrome on Android doesn't support extensions.

</details>

---

<div align="center">

Made by **[Jafran Hasan (@jafranonline)](https://www.facebook.com/jafranonline/)**


</div>
