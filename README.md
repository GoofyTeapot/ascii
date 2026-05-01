# ASCII Art Generator (Color + Adjustable Resolution)

A minimal, fast, and browser‑based ASCII art generator.  
Upload an image → get color ASCII instantly.  
Includes a resolution slider for performance control.

This project is fully client‑side and works on GitHub Pages.

---

## Features
- Convert any uploaded image into ASCII art  
- Colorized output using the original pixel RGB  
- Adjustable resolution slider (40–200 columns)  
- Very fast: single‑pass canvas processing + one DOM update  
- Zero dependencies, zero styling bloat  
- Works on desktop and mobile browsers

---

## How to Use
1. Open the site in your browser.  
2. Upload an image (`.png`, `.jpg`, `.jpeg`, etc.).  
3. Adjust the resolution slider in the top‑right to increase or decrease detail.  
4. The ASCII output updates instantly.

---

## Performance Notes
- Higher resolution = more ASCII characters = more CPU usage.  
- Lower resolution = faster rendering.  
- The slider lets you balance detail vs speed depending on your device.

---

## Hosting on GitHub Pages
1. Create a new repository.  
2. Add `index.html` to the root.  
3. Go to **Settings → Pages**.  
4. Set source to **main branch / root**.  
5. Your site will be live at:  
   `https://<your-username>.github.io/<repo-name>/`

---

## License
This project is free to use, modify, and host anywhere.
