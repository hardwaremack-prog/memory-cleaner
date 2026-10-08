# Memory Cleaner

A free, portable tool that frees up RAM on Windows using Windows' own memory-management functions. Handy right before a game or a heavy program needs a big block of free memory.

![Memory Cleaner screenshot](<Memory Cleaner - screenshot (from manual).png>)

## Why it matters now: RAM has never been this expensive

Since late 2025 the world has been in a memory shortage, nicknamed **"RAMageddon."** Memory makers are selling most of what they produce to AI data centers. That leaves far fewer chips for everyday PCs, and prices have shot up:

| What you're buying | About a year ago | In 2026 |
|---|---|---|
| 32 GB DDR5 kit | $75–$125 (Jan 2025) | ~$325+ |
| 64 GB DDR5-5600 kit | $191 (Aug 2025) | $1,118 (Aug 2026), up about 485% |

DDR4 isn't safe either. It has climbed sharply too. Analysts expect the shortage to last into 2027 or 2028. The squeeze is showing up everywhere: the Steam Deck went up by more than $200, and makers such as Samsung and Framework have warned customers about higher prices.

**So the smart move is to do more with the memory you already have.** That's what Memory Cleaner is for. It can't add RAM to your PC. What it does is use Windows' own tools to hand back memory that's being held but not used. This helps most on 8–16 GB machines that start to bog down when a game, a browser full of tabs and a few apps are all open together. Before you spend hundreds on an upgrade, see how far your current RAM can go.

<sub>Sources: [Tom's Hardware RAM price index](https://tomshardware.com/pc-components/ram/ram-price-index-2026-lowest-price-on-ddr5-and-ddr4-memory-of-all-capacities) · [Tech Insider (Sept 2026)](https://tech-insider.org/ca/?p=1254) · [TweakTown](https://www.tweaktown.com/news/109222/ram-shortages-are-here-until-2028-64gb-ddr5-is-now-dollars500-256gb-ddr4-costs-over-dollars3000/index.html) · [Channel News, CES 2026](https://www.channelnews.com.au/ces-2026-samsung-warns-ram-shortage-will-drive-consumer-tech-price-hikes/). Prices change fast, so check current prices before you buy.</sub>

## What it does

- Clears up to eight memory areas, such as the standby list and working sets, and shows how much it freed
- Run it with a button, a hotkey, or from the system tray icon
- **Automatic optimization** on a timer, or whenever memory use passes a level you choose
- The tray icon changes color with memory use
- Command-line options for scripts and shortcuts
- Portable: one small program file, no install. Settings are saved in `MemoryCleaner.ini` next to it

## Run it

Needs Windows 10 or 11 (7 and 8.1 also work) and an administrator account.

1. Put the files in a folder you'll keep, such as `C:\Tools\MemoryCleaner`
2. Double-click `MemoryCleaner.exe`
3. If Windows shows "Windows protected your PC," click **More info**, then **Run anyway** (the program isn't digitally signed)
4. Click **Yes** on the admin prompt, then click **Optimize**

The full guide is in `Memory Cleaner - User Manual.pdf`, and `README.txt` is a one-page quick reference.

---
Made by hardwaremack.
