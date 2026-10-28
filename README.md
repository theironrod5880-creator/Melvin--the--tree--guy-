# Melvin the Tree Guy

A single-file homepage for **Melvin the Tree Guy** — a locally owned tree service
offering trimming, removal, logging, brush removal, stump grinding, firewood, and
storm damage cleanup.

Built with plain HTML/CSS/JS. No frameworks, no build step, no external files.
Drop it on GitHub Pages and it's live.

## 🌳 What's on the page

- **Free estimates banner** at the very top
- **Sticky header** with "Call Now" and "Messenger" buttons always visible
- **Hero section** with the phone number and Facebook links as the primary actions
- **7 service cards**: tree trimming, tree removal, logging, brush removal,
  stump grinding, firewood, storm damage cleanup
- **"Why Melvin" trust section**
- **Contact card** with big call + Messenger buttons and the phone/FB details
- **Footer** with services and contact info
- **Fully responsive** and phone-first (this page is designed to be used from a phone)

## 📞 Business Info Wired In

| Item | Value |
|---|---|
| Business name | Melvin the Tree Guy |
| Phone | (417) 969-8066 — tap-to-call: `tel:+14179698066` |
| Facebook / Messenger | https://www.facebook.com/profile.php?id=61593145693724 |
| Estimates | Free |

**Note:** The Facebook URL is a profile link, so it opens Melvin's Facebook profile.
From there, visitors can tap "Message" to reach him on Messenger. If you later
create a dedicated page username (e.g. `facebook.com/melvinthetreeguy`), swap
the URL in the HTML — it appears 4 times. Search for `61593145693724` to find them all.

## 🚀 Deploy on GitHub Pages (phone only)

1. Go to [github.com](https://github.com) in your phone browser and sign in.
2. Tap **+ → New repository**. Name it (e.g. `melvin-tree-guy`), set it **Public**,
   check **Add a README file**, and tap **Create repository**.
3. Tap **Add file → Create new file**, name it exactly **`index.html`**, paste the
   HTML, and tap **Commit new file**.
4. Tap **Settings → Pages**. Set branch to **`main`**, folder **`/ (root)`**, tap **Save**.
5. Wait 1–2 minutes, refresh, and your live URL appears
   (usually `https://yourusername.github.io/melvin-tree-guy/`).

## ✏️ Things to update later

- **Service area** — not listed yet; add a line in the contact card if wanted.
- **Hours** — not listed; add if Melvin wants them shown.
- **Photos** — the page uses an inline SVG tree so no image upload is needed.
  To add real job photos, upload images to the repo and add `<img>` tags in the
  service cards or a new gallery section.
- **Facebook username** — if Melvin sets one, replace the profile URL (4 places).

## 🎨 Colors

All colors are in the `:root` block at the top of the CSS. Change `--green` and
the whole site updates.

## 📄 License

Free to use and modify for this business. No attribution required.
