#HowToAddMorePhotos
---------------------------------------

This guide explains how to add new photos to your existing photography site.

1️⃣ Add new image files to your pCloud storage:
   - Place hero images in: /assets/coverimages/
   - Place gallery images in: /Images/fulls/
   - Place polaroid images in: /Images/polaroids/

2️⃣ Update manifest.json in your local repo:
   - Open the file in your editor.
   - Add new filenames under the correct category:
        "heroImages": [...],
        "galleryImages": [...],
        "polaroids": [...]
   - Make sure you only list the filenames, not the full URLs.

3️⃣ Save your changes to manifest.json.

4️⃣ Commit and push your updates to GitHub:
   git commit -m "Added new images"
   git push origin main

5️⃣ Wait 1–2 minutes for GitHub Pages to update your site.

6️⃣ Visit your site:
   https://photography.theabhisek.com/
   (or fallback: https://mohptr.github.io/Photography/)

✅ Tip:
If you don’t see the new images, clear your browser cache or do a hard refresh (Ctrl+Shift+R on Windows / Cmd+Shift+R on Mac).

---------------------------------------

✅ **That’s it!**  
Just remember:  
→ Upload to pCloud → Update `manifest.json` → Commit → Refresh.
