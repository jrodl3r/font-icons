# Font-Icons
Create your own custom CSS Font Icons in a few easy steps!

## Usage Guide
**1. Install FontCustom:** https://github.com/FontCustom/fontcustom

**2. Update SVG icons in the `/icons` folder:**

**3. Build Assets:** `fontcustom compile icons`

**4. Add Icons:**
- Move the `/fontcustom` folder to your project and include: `fontcustom/fontcustom.css`
- Access icons by creating a tag with the class: `icon-{{SVG_FILENAME}}`:
```
  <i class="icon-home"></i>
```

## Preview
For a preview of your icons open `fontcustom-preview.html` in any browser.
