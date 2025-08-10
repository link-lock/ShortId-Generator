# 🔗 ShortId Generator for VLESS/VMESS REALITY

A simple web tool to generate short identifiers (shortIds) used in VLESS/VMESS REALITY configs. If you're tired of creating them manually — this generator will do the job for you.

## 🌐 Quick Start

**🖥️ Live version:** [link-lock.github.io/ShortId-Generator](https://link-lock.github.io/ShortId-Generator)

**📂 GitHub profile:** [github.com/link-lock](https://github.com/link-lock)

## 📋 What are shortIds?

ShortIds are essential components of VLESS/VMESS REALITY configurations:

- **Format:** Short hexadecimal strings (0–9, a–f)
- **Length:** From 2 to 16 characters
- **Purpose:** Used in VLESS/VMESS REALITY configs for additional security
- **Usage:** Multiple shortIds can be set — the client will pick one randomly

## 🚀 Features

✨ **Smart Generation**
- Generate 1–20 random shortIds at once
- Choose custom length (2–16 characters)
- Guaranteed unique values — no duplicates

📋 **Multiple Output Formats**
- **JSON array** - Ready for direct config integration
- **Compact format** - Quick copy-paste into configs
- **Plain list** - Simple values for manual use

🎯 **User Experience**
- One-click copy button for quick copying
- Responsive design — works on desktop, tablet, and mobile
- Clean, intuitive interface

## 🖥️ Alternative Methods

### Using Xray CLI
```bash
xray uuid -i shortuuid
```

### Using Python
```python
import secrets
secrets.token_hex(8)  # Generates 16 characters
```

## 📦 How to Use

### Option 1 — Online (Recommended)
1. Open [ShortId Generator](https://link-lock.github.io/ShortId-Generator) in your browser
2. Set the desired quantity and length
3. Click **🎲 Generate**
4. Copy the result using the copy button

### Option 2 — Local Installation
1. Download `index.html` from the repository
2. Open it in any modern browser
3. Set the quantity and length parameters
4. Click **Generate**
5. Copy and paste the results into your config

## 🛠️ Technical Details

- **No dependencies** - Pure HTML, CSS, and JavaScript
- **Client-side only** - No data sent to servers
- **Cross-platform** - Works on all modern browsers
- **Lightweight** - Single HTML file

## 📄 License

**MIT License** — Free to use, modify, and distribute without restrictions.

---

<div align="center">

**⭐ Star this repository if you find it helpful!**

Made with ❤️ for the VLESS/VMESS community

</div>
