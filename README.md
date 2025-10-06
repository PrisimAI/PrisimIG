# PrisimIG

PrisimIG is a **powerful, browser-based AI image generator** with a sleek **liquid glass UI**. It allows users to generate images using **Flux** and **Turbo** models with full customization options, prompt history, batch generation, and more.  

Built with **HTML, CSS (Tailwind), and JavaScript**, it’s designed to feel like a professional tool while remaining lightweight and fast.

---

## 🌟 Features

- **AI Models**: Choose between `Flux` and `Turbo` for different image generation styles.
- **Prompt History**: Automatically saves your recent prompts for easy reuse.
- **Batch Generation**: Generate up to 5 images at once.
- **Image Variations / Remix**: Right-click on any image to generate a new variation.
- **Advanced Controls**:  
  - Select image **size** (`256x256`, `512x512`, `1024x1024`)  
  - Choose **style** (`Anime`, `Realistic`, `Cartoon`, `Fantasy`)  
  - Set a **seed** for reproducible outputs
- **Download Images**: Save your generated images with one click.
- **Draggable Images**: Reorder your generated images in the feed.
- **Ultra Liquid Glass UI**: Sleek glassmorphism with animated gradients and soft shadows.
- **Dark Mode Support**: Toggle between light and dark themes.
- **Responsive Layout**: Optimized for desktop and mobile.

---

## ⚡ How to Use

1. Open `index.html` in your browser.
2. Type your prompt into the **prompt box**.
3. Select your desired **model**, **size**, and **style**.
4. Optionally, enter a **seed** for reproducible results.
5. Choose your **batch size** (1–5) if you want multiple images.
6. Click **Generate Image**.
7. Right-click on any image to remix it.
8. Download images using the **Download** button below each image.
9. Clear the feed with the **Clear Images** button.

---

## 💻 Installation

1. Clone or download the repository.
2. Open `index.html` in any modern browser.
3. Optional: Add a Service Worker for offline caching (`sw.js` included).

---

## 🔧 Customization

- **Colors & Theme**: Edit `:root` CSS variables or Tailwind classes.
- **Glassmorphism Strength**: Adjust `backdrop-filter`, `opacity`, or gradient animations.
- **API Key**: Replace the `apiKey` in the script with your own if needed.

---

## ⚙️ API Integration

- Uses **[Pollinations AI](https://image.pollinations.ai/)** for image generation.
- Supports `Flux` and `Turbo` models.
- Includes parameters for:
  - `size` (image dimensions)  
  - `style` (art style)  
  - `seed` (reproducibility)  

---

## 🛠 Tech Stack

- **HTML5 & CSS3**
- **Tailwind CSS**
- **JavaScript (Vanilla)**
- **Service Worker** (offline caching)
- **Pollinations AI** for image generation

---

## 📂 Project Structure

```
PrisimAI/
│
├─ index.html          # Main application
├─ sw.js               # Service worker (optional)
├─ styles.css          # Custom styles (optional, mostly inline)
├─ README.md           # This file
├─ favicon.ico         # Site icons
└─ assets/             # Any images or assets
```

---

## 🚀 Future Improvements

- Sliders for **creativity, realism, and style intensity**
- **Export multiple images** as GIFs or ZIP
- **Offline AI support** using WebLLM
- **User accounts** with saved image history
- **Sharing to social media** directly

---

## 📜 License

MIT License – free to use, modify, and distribute.
