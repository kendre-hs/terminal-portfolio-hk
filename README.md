# GemiOS Terminal Portfolio 🚀

An interactive, retro-styled CLI terminal portfolio built using HTML, CSS, JavaScript, **Three.js** (for 3D visualization), and **Tone.js** (for interactive audio synthesizer feedback).

Developed for **Mr. Kendre Hanumant Shesherav**, AI/ML Engineer.

---

## 🌟 Key Features

- **📺 Retro CRT Effect**: Classic terminal aesthetic with scanlines and subtle flicker animations.
- **🔊 Interactive Audio**: Real-time synth-sound feedback on keypresses and animations powered by **Tone.js**.
- **🔮 3D Skills Sphere**: Dynamic interactive 3D Tag Cloud built using **Three.js** showing proficiencies on hover.
- **⌨️ CLI Command Interface**: Execute terminal-like commands to learn about profile history, projects, and contact channels.
- **✨ Glitch Animations**: High-tech retro glitch animations for section headers.
- **📱 Fully Responsive**: Custom sizing and interactive elements scaled across both desktop and mobile screens.

---

## 🛠️ Commands Available

Type these commands in the terminal prompt (`>`) and press **Enter**:

| Command | Description |
| :--- | :--- |
| `about` | Displays background, biography, and professional profile summary. |
| `skills` | Renders the interactive 3D skills sphere tag cloud. |
| `projects` | Opens the featured project highlights modal grid. |
| `contact` | Reveals links to LinkedIn, GitHub, email, and an interactive message box. |
| `clear` | Clears the terminal screen of all previous logs. |
| `reboot` | Restarts the OS session and restarts the boot sequence. |

---

## 🚀 How to Run Locally

Since the project uses external libraries (Three.js and Tone.js) loaded via CDN, you can run it easily:

1. **Open directly**:
   Double-click the `indexp.html` (or `index.html`) file to launch it in any modern web browser.
   
2. **Serve via Local HTTP Server**:
   For the best experience, you can serve it using Python or Node:
   ```bash
   # Python (Python 3+)
   python -m http.server 8000

   # Node.js (npx)
   npx http-server
   ```
   Open `http://localhost:8000` (or `8080`) in your web browser.

---

## 🌐 Deployment to GitHub Pages

To host this portfolio live on the web:
1. Go to your GitHub repository **Settings**.
2. Click **Pages** in the left sidebar menu.
3. Under **Build and deployment**, set the Source branch to **`main`** and folder to `/ (root)`.
4. Click **Save**. 
5. Your portfolio website will be live at `https://<your-username>.github.io/<your-repo-name>/`.
