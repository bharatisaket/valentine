# 💘 The Love Eras Tour: A Swiftie Valentine's Proposal

A custom-built, interactive web experience designed to ask the ultimate question: *"Will you be my Valentine?"* Inspired by Taylor Swift's Eras Tour, this project takes the user on a journey through three musical eras, featuring synced lyrics, interactive buttons, and a dynamic "Ticket" generation finale.

## ✨ Features

* **🎵 Era-Based Navigation:** Transitions seamlessly between *Reputation* (Intro), *Lover* (The Question), and *Midnights* (The Ticket) aesthetics.
* **🎤 Perfectly Synced Lyrics:** Uses an internal LRC parser to sync lyrics to the millisecond with the audio.
* **🏃‍♂️ The "Runaway" Button:** The "No" button uses proximity detection math to intelligently dodge the cursor, ensuring it never overlaps the "Yes" button or leaves the visible area.
* **🖱️ Custom Cursors:** Context-aware cursors (Sparkles default, Arrow Heart for "Yes", Broken Heart for "No").
* **📱 Responsive Design:** Optimized for both Desktop and Mobile views.
* **🎟️ Dynamic Ticket Generator:** Generates a personalized "Eras Tour" ticket upon acceptance with a unique barcode.

## ⚠️ Important: Disclaimer & Usage Policy

**This project is created strictly for personal and educational purposes.**

* **No Piracy Intended:** This repository contains **source code only** (HTML/CSS/JS). It **does not** contain any copyrighted audio files.
* **Personal Use Only:** I do not promote piracy. This code is intended to be used as a personal romantic gesture. It is not intended for commercial distribution, sale, or monetization.
* **Audio Rights:** I do not own the rights to the music referenced in this project. All rights belong to **Taylor Swift** and her respective record labels. Users must supply their own legally obtained audio files to use this project.

## 🚀 How to Set Up

1.  **Clone or Download** this repository.
2.  **Add Your Audio Files:**
    * You must provide your own MP3 files for the site to work.
    * Rename your files exactly as follows:
        * `song1.mp3` (...Ready For It?)
        * `song2.mp3` (Cruel Summer)
        * `song3.mp3` (Mastermind)
    * Place them in the main folder next to `index.html`.
3.  **Run Locally:** Double-click `index.html` to open it in your browser.
4.  **Deploy Online:** Upload the files (HTML + your MP3s) to **GitHub Pages** or **Netlify Drop** to share the link.

## 🛠️ How to Customize (Venue, Date, Time)

You can easily change the details on the final "Ticket" screen to match your actual Valentine's Day plans.

1.  Open `index.html` in any text editor (Notepad, VS Code, TextEdit).
2.  Press **Ctrl+F** (or Cmd+F) and search for the text **"Your Fav Restaurant"**.
3.  Replace the text inside the HTML tags with your actual plan.

**Example Code Change:**

*Look for this block (approx. line 230):*
```html
<div class="ticket-row"> 
    <div><div class="label">Date</div><div class="value">Feb 14, 2026</div></div> 
    <div><div class="label">Time</div><div class="value">07:00 PM</div></div> 
</div>
<div class="ticket-row"> 
    <div><div class="label">Venue</div><div class="value">Your Fav Restaurant</div></div> 
</div>
```
Change it to:
```html
<div class="ticket-row"> 
    <div><div class="label">Date</div><div class="value">Feb 14, 2026</div></div> 
    <div><div class="label">Time</div><div class="value">08:00 PM</div></div> 
</div>
<div class="ticket-row"> 
    <div><div class="label">Venue</div><div class="value">Olive Garden 🍝</div></div> 
</div>
```
💖 Credits

Inspiration: Taylor Swift 

Are you ready for it? 🐍💖🕰️

