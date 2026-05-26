# Sadik Bhattarai — Portfolio Website

> AI & Bioinformatics · PhD Scholar · K-Influencer 2025 · South Korea

A professional single-page portfolio built with pure HTML, CSS, and JavaScript — no frameworks, no build step, zero dependencies. Deploy anywhere in seconds.

---

## 🚀 Deploy on GitHub Pages

1. **Create a new GitHub repository** (e.g. `sadik-portfolio`)
2. **Upload `index.html`** to the root of the repo
3. Go to **Settings → Pages**
4. Set source to **Deploy from branch → main → / (root)**
5. Click **Save** — your site will be live at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

---

## ✏️ Personalise the Content

Open `index.html` and update these sections:

| What to change | Where to find it |
|---|---|
| Profile photo | `src="https://sadik96.netlify.app/1.jpeg"` — replace with your own image URL or add `photo.jpg` to the repo and change to `src="photo.jpg"` |
| Email address | `href="mailto:sadik@example.com"` and the visible text |
| GitHub link | `href="https://github.com/"` → your GitHub URL |
| LinkedIn link | `href="https://www.linkedin.com/"` → your LinkedIn URL |
| Publications | Search for `pub-item` blocks and update titles, authors, venues |
| Social stats | Update numbers in `social-metric` spans (YouTube, Instagram etc.) |
| Education timeline | `timeline-item` blocks under the Education heading |
| Skills & percentages | `skill-item` blocks + `data-width` attributes |
| Stat counters | `data-count` attributes on `.stat-num` elements |

---

## 🎨 Customise the Design

All colours are CSS variables at the top of `<style>`:

```css
:root {
  --bg:      #050c12;   /* page background */
  --cyan:    #00d4aa;   /* academic accent */
  --orange:  #ff7043;   /* influencer accent */
  --gold:    #f5c842;   /* award/badge colour */
}
```

---

## 📁 File Structure

```
/
└── index.html    ← entire site (self-contained)
└── README.md     ← this file
└── photo.jpg     ← (optional) local profile photo
```

---

## 📬 Contact Form

The form currently shows a success message in-browser (demo mode). To make it functional, integrate a free service like **Formspree**:

1. Go to [formspree.io](https://formspree.io) and create a free form
2. Replace the `handleSubmit()` function with a `fetch` POST to your Formspree endpoint

---

Built with ❤️ using HTML · CSS · JS — no frameworks needed.
