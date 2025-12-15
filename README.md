# 🔗 Reese's Minimal Link Hub (Linktree Alternative)

Welcome to my custom link page! This site acts as my central hub for all my online profiles, designed with a minimal, hacker-terminal aesthetic using the Dracula color palette.

It's self-hosted, lightweight, and uses plain HTML/CSS for speed.

---

## 🚀 How to Use This Link

This entire page is contained within a single HTML file (`index.html` or `22.html`).

**To use this link on Instagram (or anywhere else):**

1.  **Host it:** The file must be hosted live (e.g., using GitHub Pages, Netlify, or Vercel).
2.  **Copy the URL:** Grab the full `https://` URL provided by your hosting service.
3.  **Paste it:** Put that URL into the "Links" section of your Instagram profile.

---

## 🔧 Maintenance and Editing

Need to change a link or update the text? It's simple:

1.  **Open the file:** Navigate to `index.html` (or `22.html`) in this repository.
2.  **Edit:** Click the pencil icon to edit the file directly on GitHub.
3.  **Look for the links:** Scroll down to the `<div class="link-group">` section. Each link is clearly defined:

    ```html
    <a href="PASTE_YOUR_NEW_URL_HERE" class="link-btn" target="_blank">
        <i class="fab fa-instagram icon"></i>
        <span class="link-text link-text-1">new_link_title</span>
    </a>
    ```

4.  **Commit:** Save your changes by clicking "Commit changes" at the bottom. GitHub Pages will automatically update your live link within minutes.

### Key Customizations:

| Item | Location in Code | What it does |
| :--- | :--- | :--- |
| **Profile Name** | `<h1>Reese</h1>` | Your main displayed name. |
| **Subtitle** | `<div class="subtitle">...</div>` | The small text under your name (`~/bc/link/tree/sucks`). |
| **Profile Photo** | `<img src="...">` | Uses an auto-generated image based on your name. To use a real photo, replace the `src` URL with a direct link to your photo (needs to be a square image). |

---

## 🎨 Design Philosophy

* **Aesthetic:** Catpuccin Mocha (dark background, neon accents).
* **Font:** JetBrains Mono (coding/terminal font).
* **Animations:** Subtle float on the container, simultaneous typing effect on links, and a neon glow on button hover.

Thanks for checking out the repo!
