# Font-Icons
Roll your own custom CSS Font Icons in a few easy steps...

## Usage Guide
**1. Install FontCustom:** https://github.com/FontCustom/fontcustom

**2. Update SVG icons in the `/icons` folder:**

**3. Build Assets:** `fontcustom compile icons`

**4. Add Icons:**
- Move the `/fontcustom` folder to your project.
- Include `fontcustom/fontcustom.css` in your index.
- Access the icons by creating a tag with the class `icon-{{SVG_FILENAME}}`:
```
  <i class="icons-home"></i>
```

## Preview
For a nice preview showcasing various sizes of your icon checkout the generated `fontcustom-preview.html` file in any browser.
