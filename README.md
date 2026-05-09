# Happy Mother's Day, Ashley! 🌸

A Mother's Day website made with love by the whole family.

## Hosting on GitHub Pages

1. Go to [github.com](https://github.com) and create a new **public** repository (e.g. `mothers-day-ashley`)
2. Upload all these files to the repository (drag & drop onto the repo page, or use `git push`)
3. Go to **Settings → Pages**
4. Under **Source**, select **Deploy from a branch**
5. Choose `main` branch and `/ (root)` folder, then click **Save**
6. After ~60 seconds your site will be live at:
   `https://YOUR-USERNAME.github.io/mothers-day-ashley/`

---

## Adding Real Photos

For each placeholder, open the relevant HTML file and find the `photo-placeholder` div. Replace it with an `<img>` tag:

```html
<!-- Before -->
<div class="photo-placeholder">
  <span class="ph-icon">📷</span>
  <span class="ph-text">Family Photo</span>
</div>

<!-- After -->
<img src="images/family-1.jpg" alt="Family photo">
```

Put your photo files inside the `images/` folder. Keep filenames simple (no spaces).

---

## Customizing the "Why I Love You" Messages

In each person's HTML file, find the `<ul class="reasons-list">` section and swap out the placeholder text with your own heartfelt words. Each reason lives inside a `<span>` next to the number:

```html
<li>
  <span class="reason-num">1</span>
  <span>Write your reason here...</span>
</li>
```

---

## File Structure

```
mothers-day-website/
├── index.html       ← Landing page (family photos + nav cards)
├── brooklyn.html    ← Brooklyn's page
├── mason.html       ← Mason's page
├── liam.html        ← Liam's page
├── austin.html      ← Austin's page
├── from-me.html     ← Your page (husband)
├── style.css        ← All styles (shared across every page)
└── images/          ← Drop your photos here
```
