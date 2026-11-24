# 🎨 Art Vibe Detective

**Art Vibe Detective** is a single-screen, pass-and-play family party game where players decode poetic, sideways "vibe clues" and minimalist geometric shape hints to identify famous works of **Painting**, **Sculpture**, and **Architecture**.

Built as a single, zero-dependency HTML file (`index.html`), it works offline, loads instantly on any phone or tablet, and requires no accounts, logins, or internet connections to play.

---

## ✨ Features

* **Pass-and-Play Party Format:** Designed for 2 to 4 players sharing one phone, tablet, or laptop around a table.
* **Balanced Multi-Medium Gallery:** Features 18 curated masterpieces spanning **Painting** (6), **Sculpture** (6), and **Architecture** (6).
* **Fair Turn Scaling:** Automatically deals 6 rounds for 2–3 players and 8 rounds for 4 players so every player gets an equal number of turns.
* **Abstract Visual Hints:** Every round includes a custom, minimalist geometric & color-palette SVG hint alongside a non-literal poetic description.
* **Educational Gallery Notes:** Solving a round reveals a brief, memorable historical fun fact about the artwork.
* **Zero Dependencies & Privacy-First:** 100% self-contained plain HTML, CSS, and JavaScript. No external fonts, images, libraries, analytics, or personal data collection.

---

## 🕹️ How to Play

1. **Choose Player Count:** Select **2 Players**, **3 Players**, or **4 Players** on the start screen and tap **Start Game**.
2. **Inspect the Clues:** On your turn, examine the abstract shape/color illustration and read the poetic "vibe clue" aloud to the table.
3. **Make Your Guess:** Tap the matching artwork title and creator from the four choices:
   * **First-Try Solve:** Earns **+1 point** for the active player.
   * **Missed Guess:** Eliminates that option with a gentle prompt so you can keep guessing until the mystery is solved.
4. **Win the Game:** After all rounds are complete, the player with the highest score is crowned the **Art Vibe Detective**! Tap **Play Again** to shuffle a fresh set of artworks.

---

## 📁 Repository Structure

```text
art-vibe-detective/
├── index.html      # Complete, self-contained game (HTML, CSS, SVG art, and JS)
└── README.md       # Project overview and GitHub Pages setup guide
```

> **Note:** If you saved your game file as `art_vibe_detective.html`, rename it to `index.html` when uploading to GitHub so GitHub Pages loads it automatically at your main URL.

---

## 🚀 How to Publish on GitHub Pages

1. **Create a Public Repository:**
   * Sign in to [GitHub](https://github.com) and click **New** to create a new repository (for example, `art-vibe-detective`).
   * Make sure the repository is set to **Public**.
2. **Upload Your Files:**
   * Click **Add file** → **Upload files** (or push via Git).
   * Upload `index.html` (your game file) and this `README.md` file, then click **Commit changes**.
3. **Enable GitHub Pages:**
   * Go to your repository's **Settings** tab.
   * In the left sidebar, click **Pages**.
   * Under **Build and deployment** → **Branch**, select `main` (and `/ (root)`), then click **Save**.
4. **Share & Play:**
   * Wait 1–2 minutes and refresh the **Pages** settings screen. Your live game link (e.g., `https://<your-username>.github.io/art-vibe-detective/`) will appear at the top—ready to bookmark on your phone or text to family and friends!

---

## 🛠️ Running Locally

No build tools, package managers, or local servers are needed:

1. Download or clone this repository.
2. Double-click `index.html` (or open it via **File → Open File** in Chrome, Safari, Firefox, or Edge).

---

## 🎨 Included Artworks

* **Paintings:** *The Starry Night* (Van Gogh), *The Scream* (Munch), *The Persistence of Memory* (Dalí), *Girl with a Pearl Earring* (Vermeer), *The Great Wave off Kanagawa* (Hokusai), *Mona Lisa* (Da Vinci).
* **Sculptures:** *The Thinker* (Rodin), *David* (Michelangelo), *Balloon Dog* (Koons), *Statue of Liberty* (Bartholdi), *Cloud Gate* (Kapoor), *Venus de Milo* (Alexandros of Antioch).
* **Architecture:** *The Eiffel Tower* (Eiffel), *Sydney Opera House* (Utzon), *The Taj Mahal* (Lahori), *Fallingwater* (Wright), *Guggenheim Museum Bilbao* (Gehry), *The Colosseum* (Vespasian & Titus).