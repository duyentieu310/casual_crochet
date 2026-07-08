# My Crocheted Bags - Hugo Site

This site is ready for you to add your crocheted bags content and photos. You only need to:

## 📸 Adding a New Bag

1. **Create a folder** for your bag:
   ```
   content/bags/your-bag-name/
   ```

2. **Create an `index.md` file** inside that folder with this format:

   ```markdown
   ---
   title: "Your Bag Name"
   date: 2026-05-22
   description: "Short description shown in grids (1-2 lines)"
   thumb: "main-image.jpg"  # OPTIONAL: for grid/thumbnails
   # images: ["main.jpg", "detail.jpg", "lifestyle.jpg"]  # OPTIONAL: all images for detail page
   tags: ["tote", "summer", "market"]  # OPTIONAL: e.g., ["tote", "beach", "everyday"]
   categories: ["Bags"]  # OPTIONAL but recommended
   ---

   ## Description

   [Your detailed description here - supports markdown]

   ## Materials
   - Material 1
   - Material 2
   - etc.

   ## Dimensions
   - Width: X inches/cm
   - Height: Y inches/cm
   - Depth: Z inches/cm (if applicable)
   - Handle: W inches/cm (if applicable)

   ## Care Instructions
   [How to care for the bag]

   ![Main Shot](images/main-image.jpg)
   *Primary product shot*

   ![Detail](images/detail-image.jpg)
   *Close-up of texture or stitching*

   ![Lifestyle](images/lifestyle-image.jpg)
   *Bag in use/context*
   ```

3. **Add your photos** to:
   ```
   content/bags/your-bag-name/images/
   ```
   - Use clear, well-lit photos showing front, details, and lifestyle shots
   - Reference them in the markdown as shown above
   - The `thumb` image (if specified) is used for grid views

## 🎨 Customization (Optional)

If you want to change colors or fonts later:
- Edit `assets/css/custom.css`
- Change `--accent-color` in the `:root` section to match your yarn palette
- Adjust fonts in the CSS if desired

## 🚀 Previewing Your Site

To see your changes locally:
```bash
hugo server -D
```
Then visit: http://localhost:1313

## 🌐 Deploying When Ready

When you're ready to go live:
```bash
hugo
```
This creates a `public/` folder with all your static site files. Deploy this folder to:
- Netlify (drag & drop)
- Vercel  
- GitHub Pages
- Any web host

## 💡 Tips for Best Results

- **Photo Quality**: Use natural light, avoid flash, show multiple angles
- **Consistent Tags**: Use tags like "tote", "market", "beach", "everyday", "clutch"
- **Engaging Descriptions**: Share what makes each bag special - the inspiration, stitch pattern, or intended use
- **Update Regularly**: Add new bags as you create them
- **About Page**: Edit `content/about/_index.md` to share your story and contact information

Your site is now ready! Simply add bags following the format above, and your beautiful crocheted creations will be showcased in a clean, minimal, Fillmore-inspired gallery.