# 🎬 YouTube Retro 2010 Theme

> A custom Stylus theme that transforms YouTube into its classic 2010 look — flat, simple, and nostalgia-packed.

[![Install directly](https://img.shields.io/badge/Install%20on-UserStyles.world-blue?style=flat&logo=stylus)](https://userstyles.world/style/24168/youtube-2010)

---

## 📜 About

**YouTube Retro 2010** is a lightweight userstyle that visually reverts modern YouTube to its early 2010 aesthetic:

- Flat layout with square edges  
- Classic white & gray background  
- No Material Design shadows or icons  
- Basic system fonts (Arial, Helvetica, etc.)  
- Cleaner sidebar and video grid  
- Optional retro logo  

Built for the [Stylus browser extension](https://add0n.com/stylus.html). No JavaScript, just pure CSS.

---

## 🚀 Installation

### 🔗 One-click Install  
👉 [Install via UserStyles.world](https://userstyles.world/style/24168/youtube-2010)

### Manual Install (via Stylus)

1. Install the [Stylus extension](https://add0n.com/stylus.html)  
2. Open Stylus and create a new style  
3. Paste the contents of `youtube-retro-2010.user.css`  
4. Save and reload YouTube  

---

## 🎨 Features

- Mimics YouTube’s 2010 visual style  
- Light gray sidebar and white backgrounds  
- Simplified typography and layout  
- Removes rounded corners, shadows, and icon clutter  
- Optional retro logo (2011 style)  

---

## ⚙️ Optional: Retro Logo

Replace the modern YouTube logo with an old-school one:

```css
#logo-icon-container::before {
  content: url("https://upload.wikimedia.org/wikipedia/commons/7/75/YouTube_icon_2011.svg");
  display: block;
  width: 100%;
  height: auto;
}
#logo-icon {
  display: none !important;
}
```

---

## 📷 Screenshots

> _Add screenshots here to show before/after YouTube UI changes._  
> Recommended: homepage, video page, sidebar.

---

## ✅ Tested On

- YouTube.com (Desktop)  
- Chrome + Stylus  
- Firefox + Stylus  
- Opera + Stylus
- Last tested: September 2025  

---

## 📁 Project Structure

```
/
├── youtube-retro-2010.user.css   # The Stylus-compatible userstyle
├── README.md                     # This file
└── LICENSE                       # MIT license
```

---

## 📄 License

MIT License  
See [`LICENSE`](./LICENSE) for full terms.

---

## 👤 Author

**PixelPaw Paramounth**  
[UserStyles.world Profile](https://userstyles.world/user/PixelPaw-Coding)

---

## 🌐 Related

- [Stylus Extension](https://add0n.com/stylus.html)  
- [UserStyles.world](https://userstyles.world/)
