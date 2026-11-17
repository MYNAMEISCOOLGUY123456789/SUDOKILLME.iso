# SUDOKILLMEOS

an arch-based distro made purely because i was bored and wanted an os that actively hates you back.

comes with an easy graphical installer so you don't have to suffer through a manual arch install. the actual suffering starts after you boot into the desktop.

> **note:** this does not actually delete your files, brick your pc, or send anything over the internet. everything runs locally. still wouldn't recommend daily driving it tho.

---

## what's inside

* **browser downloads:** plays the old 90s *"YOU'VE GOT MAIL!"* sound every time a download finishes.
* **terminal downloads:** running `pacman`, `yay`, `curl`, `wget`, or `git` plays *"OH MY GOD, THEY KILLED KENNY! YOU BASTARDS!"* when it finishes.
* **typo punishment:** mistype a command or fail anything in the terminal and it blasts *"YOU ARE AN IDIOT HAHAHAHAHA!"* (spamming enter stacks the audio).
* **microslop autocorrect:** typing `microsoft` anywhere in the os (browser, terminal, text editors, whatever) automatically changes it to `microslop`.
* **locked documents:** trying to open text files forces you to beat a memory matching game first.
* **tux chaos toggle:** there's a switch in settings that summons tux onto your screen with a mallet to break your desktop and walk off.
* **`help me` trap:** typing `help me` in the terminal takes a picture with your webcam, drops it into `~/Downloads` (which triggers *"you've got mail"*), and opens a borderless window of your face that runs away from your mouse when you try to close it. *(if you're in a vm with no webcam, it roasts you for hiding in a vm instead).*

---

## secret commands & boss fights

<details>
<summary><b>spoilers (click if you're stuck or testing it for a video)</b></summary>

### `sudo ???` (bullet hell)
running `sudo ???` pulls you into a 3-heart undertale-style bullet hell fight against the terminal. survive to prove your worth. lose all 3 hearts and it kicks you back to the login screen.

### `sudokillme` (RANS0M3? boss fight)
running `sudokillme` makes a gun show up, shoot your screen, and start a boss fight called **RANS0M3?**. you get 60 seconds to find and double-click 3 key files hidden in your folders while sirens go off. if you find them, you win. if time runs out, the os reboots.

### `rm -rf` (the cursed version)
instead of actually deleting anything, running `rm -rf` sends you to a cursed version of the os:
* wallpaper turns into *obey the walrus* on loop with audio
* *username 666* starts playing
* app icons turn into creepy staring faces and red eyes follow your cursor
* scary sounds play in the background

the only way out is typing **`rm -rf OS`** in the terminal.

</details>

---

## versions

* **vm-safe version:** lets you run everything inside virtualbox / qemu / vmware without breaking anything.
* **bare-metal edition:** checks if you're in a virtual machine on startup. if it detects a vm, it cranks the volume, blasts alarms, and intentionally breaks/reboots the vm until you install it on real hardware like a normal person.

---

## status
currently building this on my 7th bare-metal partition on my laptop. iso dropping soon.

star the repo if you wanna see where this goes.

