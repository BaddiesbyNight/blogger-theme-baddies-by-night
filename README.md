# 🧷 Baddies By Night — Blogger Theme

A darkly elegant and feature-rich Blogger theme crafted for writers, lexicographers, creators, and nocturnal thinkers. **Baddies By Night** combines gothic cyber aesthetics with full responsiveness, structured post rendering, semantic SEO, and delightful interactivity — all with zero dependency on modern JS frameworks.

---

## 🛠 Features

### ✨ Aesthetic & Layout

* **Dark Cosmic Color Scheme**: Built around #0B0B10, lavender-grays, and lilac-pink hues.
* **Responsive Grid Layouts**: Adjusts fonts, logos, nav, and sidebar margins across devices.
* **Hover Glows**: Subtle neon text glows on interactive elements.
* **Back to Top Buttons**: Scroll-based visibility and smooth scrolling on click.

---

### 📱 Mobile Support

* Mobile rendering via `mobile-main`, `mobile-index-post`, and `mobile-post` templates.
* Featured thumbnail, snippet preview, comment count, and index titles adapted for touch.

---

## 📚 Blog Post Rendering

### Metadata & Structured Data

* Title, author, labels, timestamp, location, and comment count all supported.
* Rich metadata:

  * `itemprop` schema for SEO
  * Author bios with profile links and images
  * `application/ld+json` script block for Schema.org structured data

### Comments

* Threaded comments supported (`threaded_comments` includable).
* Fallback for comment disabling message.
* Optional legacy iframe-based popup preserved for compatibility.

### Share & Edit Options

* Inline share buttons per platform (`platformShare`)
* “Copy Link” option (`linkShare`)
* Email post link and quick edit available for logged-in admins.

### Labels & Location

* Label list includes emojis (🏷️)
* Location linked to Google Maps (📍)

---

## 🎵 Music Footer Player

* Embedded `<audio>` bar with play/pause toggles.
* Linked to the [MorDictionary Theme (Remastered)](https://soundcloud.com/mor-dictionary/mordictionary-theme-remastered-free-to-use-moribund-institute-suno)
* Styled for seamless integration into the footer.

---

## 📊 Widgets

### Popular Posts Grid

* Flexbox-based `.popular-posts-list` grid on homepage.
* Auto-hides on archive URLs (`/YYYY/MM/`).

### Random Post Loader

* Fetches a random post from feed and injects it into `.random-post` container.
* Only active on the homepage.

### Feed Widget

* Displays latest two posts from `WearYourDictionary` blog.
* Author/date shown; opens links in new tab.

### Stats Widget

* Uses Google Charts `sparkline` view.
* Supports `ALL_TIME` range and auto injects counter.

---

## 🔍 Search with Autocomplete

* Fetches post titles from Blogger JSON feed.
* Displays matching suggestions in a dropdown below `#search-input`.

---

## 🔔 Notification Bell & Dropdown

* `.bell-icon` toggles `.dropdown-menu` visibility.
* First link in dropdown auto-redirects to most recent post on click.

---

## 🧩 Footer

```html
<footer class="footer-container">
  ...
  <div class="footer-column">Socials</div>
  <div class="footer-column">License & GitHub</div>
  <div id="music-footer-bar">Audio Player</div>
</footer>
```

### Includes:

* Social links (YouTube, X, Reddit, Neocities)
* MIT/Unlicense via OpenSource.org
* GitHub link to [MorDictionary Blogger Theme](https://github.com/MorDictionary/blogger-theme-mor-dictionary/)
* Music player, back-to-top button, year auto-updated via JS

---

## 🧠 Technical Components

### Widgets & Includables Used:

* `Blog1` with advanced snippets (`post`, `postBody`, `postAuthor`, etc.)
* `footerBylines` and `headerByline` for multiple-author regions
* `inlineAd` conditional with placeholder
* `comment_count_picker` and `comment_picker`
* `mobile-nextprev` and `nextprev` navigation controls

### Accessibility & SEO:

* `rel="author"`, `rel="bookmark"`, `itemprop` microdata
* Semantic timestamps (`abbr.published`)
* Meta content and canonical links managed for social previews

---

## 💡 Customization Notes

* Font families: `'IM Fell English'`, `'Noto Serif JP'`, Material Icons
* Blogger’s Theme Designer support partially retained; best customized via full XML or GitHub deployment
* Highly modular: remove or swap sections using `b:includable` tags

---

## 📂 Deployment

You can deploy this theme by copying the `theme.xml` into your Blogger dashboard’s HTML editor. If using GitHub:

```bash
git clone https://github.com/MorDictionary/blogger-theme-mor-dictionary.git
```

Then follow Blogger’s instructions for uploading custom themes.

---

## 🗏 License

This theme is open-source and licensed under [The Unlicense](https://opensource.org/license/unlicense/), meaning it’s free for any use — personal, commercial, or educational.

---

## 🧫 Credits

Created by the [Moribund Institute](https://mordictionary.neocities.org/), designed to accelerate the **velocity of ideas** and equip the public with knowledge via digital dictionaries, lexical exploration, and semantic tooling.
