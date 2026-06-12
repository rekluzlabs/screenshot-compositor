React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

    @vitejs/plugin-react uses Oxc

    @vitejs/plugin-react-swc uses SWC

React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see this documentation.
Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the TS template for information on how to integrate TypeScript and typescript-eslint in your project.
Screenshot Compositor User Guide

Welcome to the Screenshot Compositor, a professional tool designed to transform raw app screenshots into store-ready marketing banners for the Google Play Store and Apple App Store. This application packages images inside sleek device mockups, overlays them with custom typography accents, and exports clean high-resolution compositions.  

1. How to Launch and Access the App

Because this is a local project, you access it via a local development server running on your machine.

    Open your terminal and navigate to the project directory.

    Install the project dependencies (only required the first time) by typing this command and hitting Enter:
    npm install

    Start the local environment server by typing this command and hitting Enter:
    npm run dev

    Once running, the terminal will provide your local web address. Open your browser and navigate to this URL:

    http://localhost:5173/


---

### 2. How to Add and Manage Screenshots

The application provides two reliable methods for loading your raw app graphics into the device mockup workspace:

#### Method A: Drag and Drop
1. Locate your raw `.png` or `.jpg` app screenshot file in your operating system's file explorer (Windows Explorer or macOS Finder)[cite: 1].
2. Click and hold the file, drag it over the dashed area labeled **Screenshot** on the left control panel, and release your mouse button[cite: 1].

#### Method B: File Browser Selection
1. Click anywhere inside the dashed **Screenshot** dropzone box[cite: 1].
2. A system dialog box will pop up. Navigate to your app's graphic assets, select the screenshot file, and click **Open**[cite: 1].

#### Updating or Removing Images
* **Replacing an Image:** To swap screenshots, simply drag a new file over the control area or click it again to select a different file. The canvas updates automatically.
* **Clearing the Canvas:** Click the **Clear** button underneath the thumbnail to purge the current image asset and revert back to the neutral placeholder state[cite: 1].

---

### Key Features

* **Instant Canvas Processing:** Renders updates locally in real-time utilizing HTML5 Canvas architecture[cite: 1].
* **Noise & Lighting FX:** Automatically embeds a procedural textured grain overlay along with dynamic radial background highlights tied directly to an accent palette configuration[cite: 1].
* **Intelligent Device Framing:** Implements clean hardware masking geometry complete with bezel styling, soft shadowing variants, and device structural components like a camera island overlay[cite: 1].
* **Copywriting Integration:** Includes built-in connection structures to generate optimized, short, structured text recommendations using the Anthropic Claude API network architecture[cite: 1].

---

### Control Panel Reference

The sidebar contains configuration settings grouped sequentially by visual impact layers[cite: 1]:

#### Branding & Background Settings
* **Background Preset Matrix:** Choose from 6 custom curated atmospheric ambient gradients[cite: 1]:
  * **Forest** (Deep Emerald Core)[cite: 1]
  * **Midnight** (Deep Cosmic Indigo)[cite: 1]
  * **Ember** (Dark Earth Vulcan Warmth)[cite: 1]
  * **Slate** (Industrial Carbon Monochrome)[cite: 1]
  * **Dusk** (Deep Twilight Violet Night)[cite: 1]
  * **Sage** (Muted Organic Moss Accent)[cite: 1]
* **Accent Color Matrix:** Defines the visual highlights for text emphasis colors, decorative hardware glowing fields, and inline badge packaging accents[cite: 1]. Choices include Green, Cyan, Amber, Rose, Violet, or White[cite: 1].

#### Structural Composition Styles
* **Layout Modes:**
  * `Top Text`: Positions typography banners near the header boundaries and pushes the graphic element device mockup downward[cite: 1].
  * `Bottom Text`: Maximizes image positioning focus upwards while tracking text descriptions at the base[cite: 1].
  * `Split`: Distributes display typographic balances evenly with centralized focus tracking across the composition vertical axis[cite: 1].
* **Text Size:** Adjusts font sizes on a multi-tier display hierarchy configuration matrix (Small, Medium, Large, XL)[cite: 1].

#### Text Composition & Marketing Inputs
* **Headline Editor:** Enter marketing slogans here[cite: 1]. Use standard line breaks (`Enter`) to break text paths across multiple rows[cite: 1]. The system targets the **final row** of your headline automatically to apply your selected accent brand highlight color colorizing format[cite: 1].
* **AI Suggest Engine:** Connects to online API endpoint architectures to translate your existing raw input description text block definitions into punchy marketing alternatives via JSON response styling models[cite: 1].
* **Subtext:** Formats an optional horizontal secondary line below the primary title blocks in a balanced neutral opacified color tint[cite: 1].

#### UI Elements & Post-Processing Toggles
* **Show Badge Toggle:** Appends a pill-shaped tag overlay below headers to display structural details like licensing or utility flags (e.g., `"Free • No Ads • Offline"`)[cite: 1].
* **Device Shadow Toggle:** Applies complex, multi-stage offset drop shadows beneath mockups to add deep dimensionality against your chosen background gradient[cite: 1].

---

### Export Generation

Click **Export PNG** to process your design[cite: 1]. The compositor spins up an offline, full-scale shadow canvas matrix to calculate perfect crisp edge geometries before prompting your system browser to save the asset[cite: 1].
