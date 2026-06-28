# ImgFrame. // Pro Photo Exif Studio

**ImgFrame** is a lightweight, high-performance web application designed for photographers and creators who need clean print margins, customized manufacturer stamps, and full exposure metadata framing without compromising their privacy.

🚀 **Live Demo:** [ImgFrame.splttr.cc](https://splttr.cc)

---

## 🛡️ Privacy First (The "No-Server" Promise)

Unlike most online image tools, ImgFrame processes **everything** on the client side.

* **No Server Uploads:** Your photos never leave your computer.
* **Local Processing:** Metadata extraction, border scaling, and canvas drawing are handled by your browser's RAM via the HTML5 Canvas and Exifr APIs.
* **Zero Tracking:** No cookies, no analytics, no remote tracking.
* **Session Purge:** Closing the tab or hitting "Reset Workspace" instantly wipes all image buffers and temporary file data from your device's memory.

---

## ✨ Features

### 1. Intelligent EXIF Extraction

* **High-Res Integrity:** Preserves the 100% original pixel dimension resolution of your source image file upon final export.
* **Auto-Discovery Arrays:** Instantly parses camera brand, model, lens profile, shutter speeds, aperture coefficients, and ISO counts.
* **Manual Override Fields:** Fine-tune or manually rewrite text fields to fix incomplete metadata or customize the text display string layout.

### 2. Proportional Framing & Assets

* **Adaptive Matte Weights:** Adjust ImgFrame margins (1.5% to 10%) automatically scaled based on the image's short side dimension for a uniform layout.
* **Dynamic Asset Hook:** Automatically reads and parses local `CamLogo - Sheet1.csv` spreadsheet templates to auto-pull official manufacturer vectors.
* **Asset Signature Vault:** Upload custom clean vector assets safely into your dashboard. They are kept securely cached using modern `localStorage` containers.

---

## 🛠️ Technical Stack

* **HTML5/JavaScript & Canvas:** Handles low-level EXIF array extraction and local compositing pipelines.
* **Exifr Engine:** High-speed client-side binary parsing for extracting metadata tags.
* **Tailwind CSS:** Modern, responsive developer grid ImgFramework configured with a native **Dark Mode** toggle.
* **Lucide Icons:** Clean, vector-based iconography mapping system.

---

## 🚀 Deployment (GitHub Pages)

This project is designed to be hosted completely for free on GitHub Pages.

1. Fork or download this repository onto your computer.
2. Keep `index.html` and your `CamLogo - Sheet1.csv` database asset together in the application's root directory.
3. Go to **Settings > Pages** inside your targeted GitHub repository configurations.
4. Select the `main` branch as your build deployment source and click **Save**.

---

## 📝 License

This project is open-source. Feel free to modify, fork, and adapt it for your own creative or professional photographic workflows.

---

*Created with ❤️ for the creative community. No pixels (or EXIF logs) were harmed (or stored) in the making of this app.*