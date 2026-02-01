# 💘 The Love Eras Tour: A Swiftie Valentine's Proposal

A custom-built, interactive web experience designed to ask the ultimate question: *"Will you be my Valentine?"* Inspired by Taylor Swift's Eras Tour, this project takes the user on a journey through three musical eras, featuring synced lyrics, interactive buttons, and a dynamic "Ticket" generation finale.

## ✨ Features

* **🎵 Era-Based Navigation:** Transitions seamlessly between *Reputation*, *Lover*, and *Midnights* aesthetics.
* **🎤 Perfectly Synced Lyrics:** Uses an internal LRC parser to sync lyrics to the millisecond with the audio.
* **🏃‍♂️ The "Runaway" Button:** The "No" button intelligently dodges the cursor using proximity detection math to ensure it never overlaps the "Yes" button.
* **🖱️ Custom Cursors:** Context-aware cursors (Sparkles default, Arrow Heart for "Yes", Broken Heart for "No").
* **📱 Responsive Design:** Optimized for both Desktop and Mobile views (Flexbox & CSS Gradients).
* **🎟️ Dynamic Ticket Generator:** Generates a personalized "Eras Tour" ticket upon acceptance.

## 🚀 How to Use

1.  **Clone or Download** this repository.
2.  **Add Audio Files:**
    * This project requires three specific MP3 files to function.
    * Rename your files to: `song1.mp3`, `song2.mp3`, and `song3.mp3`.
    * Place them in the root directory.
3.  **Run Locally:** Open `index.html` in any modern web browser.
4.  **Deploy:** Upload to **GitHub Pages** or **Netlify** to share the link with your Valentine.

## 🛠️ How to Customize (Venue, Date, Time)

You can easily change the details on the final "Ticket" screen to match your actual date plans.

1.  Open `index.html` in any text editor (Notepad, VS Code, etc.).
2.  Press **Ctrl+F** (or Cmd+F) and search for **"Your Fav Restaurant"**.
3.  Replace the text inside the div with your actual plan.

**Example Change:**
*Find this block in the code (around line 220):*
```html
<div class="ticket-row"> 
    <div><div class="label">Date</div><div class="value">Feb 14, 2026</div></div> 
    <div><div class="label">Time</div><div class="value">07:00 PM</div></div> 
</div>
<div class="ticket-row"> 
    <div><div class="label">Venue</div><div class="value">Your Fav Restaurant</div></div> 
</div>
