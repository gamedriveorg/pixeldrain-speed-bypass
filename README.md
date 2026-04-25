# ⚡ Pixeldrain Bypass Limit
**A high-performance userscript to circumvent download restrictions using multi-proxy automation.**

[![Install](https://img.shields.io/badge/Install-Userscript-orange?style=for-the-badge&logo=tampermonkey)](https://pixeldrain-bypass.gamedrive.org/pixeldrain-bypass.user.js)
[![Homepage](https://img.shields.io/badge/Homepage-GameDrive.org-blue?style=for-the-badge)](https://pixeldrain-bypass.gamedrive.org/)

---

### 🚀 Key Features
* **Seamless Bypass:** Automates the use of API-provided proxies to skip Pixeldrain’s daily download limits.
* **Dual Mode Support:** Optimized for both individual file pages (`/u/`) and gallery lists (`/l/`).
* **Bulk Downloading:** Generate proxy-protected ZIP files for entire galleries with one click.
* **Link Extraction:** Integrated popup to "Show all files," allowing you to copy direct bypass URLs or export them as a `.txt` file.
* **Performance Caching:** Proxies are cached for 24 hours in `localStorage` to ensure instant button loading and stability.

---

### 🛠 Installation & Usage
1.  **Requirement:** Install [Tampermonkey](https://www.tampermonkey.net/) or [Violentmonkey](https://violentmonkey.github.io/).
2.  **Installation:** Click the **Install Userscript** badge above.
3.  **Operation:**
    * Navigate to any Pixeldrain URL.
    * Click **Download Bypass** on file pages.
    * On gallery pages, use the vertical sidebar buttons to **Download ZIP** or **Extract Links**.

---

### 📝 Technical Details
| Feature | Description |
| :--- | :--- |
| **Network** | Uses `GM_xmlhttpRequest` for cross-origin API proxy fetching. |
| **Tab Management** | Prefers `GM_openInTab` to prevent popup blockers. |
| **Caching** | 24-hour TTL; clear browser local storage to force a proxy refresh. |
| **Privacy** | Zero data collection; links are handled locally on your machine. |

---

**Author:** [GameDrive.Org](https://pixeldrain-bypass.gamedrive.org/)  
**Support:** For updates and issues, visit the official homepage.
