# 🚀 QUICK START - Upload to GitHub in 3 Steps

## Step 1: Download Package
✓ You already have it! This folder contains everything.

## Step 2: Upload to GitHub

### Option A: Via GitHub Website (Easiest)
1. Go to: https://github.com/infodelabre/delabre
2. Click "Add file" → "Upload files"
3. Drag ALL files from this folder into the upload area
4. Scroll down, add commit message: "Update collection with 33 new items"
5. Click "Commit changes"

### Option B: Via Git Command Line
```bash
# Navigate to your local repository
cd /path/to/delabre

# Copy all files from this package
cp /path/to/delabre-website-updated/* .

# Add all files
git add .

# Commit
git commit -m "Update collection with 33 new items"

# Push to GitHub
git push origin main
```

## Step 3: View Live Site
- Wait 1-2 minutes for GitHub Pages to rebuild
- Visit: https://infodelabre.github.io/delabre/

**DONE!** ✅

---

## 📸 Replacing Placeholder Images (Later)

When you have real photos:

1. **Take 4 photos per item:**
   - Photo 1: Main view (keep the one from PDF or replace)
   - Photo 2: Detail view (replace placeholder)
   - Photo 3: Another angle (replace placeholder)
   - Photo 4: Context shot (replace placeholder)

2. **Name them exactly:**
   ```
   item-001_1.jpg
   item-001_2.jpg
   item-001_3.jpg
   item-001_4.jpg
   ```

3. **Upload to replace:**
   - Go to your GitHub repository
   - Click on the image file (e.g., item-001_2.jpg)
   - Click the trash icon to delete
   - Click "Add file" → "Upload files"
   - Upload your new photo with the SAME name
   - Commit

4. **Done!** The site will update automatically.

---

## 🔍 Finding Item Numbers

Check `items_data.json` or refer to `CHANGES.md` for the full item list with numbers.

**Quick Reference:**
- Item 001: Radica Lighter Cases
- Item 002: Silver Lighter
- Item 003: Marquetry Box
- Item 004: Bugatti Chairs
- Item 023: Janus Bust
- Item 030: Flos Toio
- ...and so on

---

## ⚠️ Important Notes

1. **DON'T delete any files** unless you know what they are
2. **KEEP the same file names** when replacing images
3. **JPG format** recommended for photos (not PNG)
4. **Max 1200px** width/height for optimal loading
5. **Items 2, 3, 4** of each set are placeholders - these are your priority to replace

---

## 💡 Pro Tips

- **Replace high-value items first:** Janus, Bugatti chairs, Hoffmann chairs, Flos Toio
- **Use consistent lighting** across all photos
- **Show scale** by including a familiar object in context shots
- **Highlight details** that make each piece special

---

## 📞 Need Help?

- GitHub Pages not updating? Wait 5 minutes, clear browser cache
- Images not showing? Check file names match exactly (case-sensitive!)
- Site not working? Make sure index.html uploaded successfully

---

**Everything is ready. Just upload and go! 🎉**
