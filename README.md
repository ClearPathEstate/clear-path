# ClearPath Estate Sales - GitHub Upload Instructions

## What's in this folder?

This is everything you need to upload to GitHub. The folder structure is already correct.

## Files included:

```
GITHUB-UPLOAD/
├── index.html                                    ← Your main website
├── 349d7199ef6c22a285dbc16b335ba412.jpg         ← LA cityscape (hero background)
├── 623cb7ec798e33b75e763c624fd1080e.jpg         ← Furniture photo 1
├── d12f29928e8ca26e90c24eecd50f45e5.jpg         ← Furniture photo 2
├── admin/                                        ← CMS admin folder
│   ├── config.yml                               ← CMS configuration
│   └── index.html                               ← CMS interface
└── content/                                      ← Content data folder
    ├── about.json                               ← About section text
    ├── contact.json                             ← Contact info
    ├── gallery.json                             ← Gallery image paths
    └── sales/                                   ← Sales folder
        ├── 2025-12-21-pasadena.md              ← Pasadena sale
        └── 2025-12-28-malibu.md                ← Malibu sale
```

## How to upload to GitHub:

### Step 1: Go to your GitHub repository
1. Go to github.com
2. Click on your `clearpath-estate-sales` repository
3. You should see the repository page

### Step 2: Upload ALL files
1. Click "Add file" → "Upload files"
2. **Drag the ENTIRE `GITHUB-UPLOAD` folder** (not individual files)
3. Wait for all files to upload
4. Scroll down and click "Commit changes"

**IMPORTANT:** Upload the whole folder at once so GitHub keeps the folder structure intact.

### Step 3: Verify files uploaded correctly
After upload, your GitHub repo should show:
- index.html
- 3 JPG files
- admin/ (folder)
- content/ (folder)

If you see these, you're good!

## Next steps (after GitHub upload):

### Connect to Netlify:
1. Go to app.netlify.com
2. Click "Add new site" → "Import an existing project"
3. Choose "GitHub"
4. Select your `clearpath-estate-sales` repository
5. Click "Deploy site"
6. Wait ~2 minutes for deployment

### Enable the CMS:
1. In Netlify, go to "Identity" tab
2. Click "Enable Identity"
3. Scroll down to "Services" → Click "Enable Git Gateway"
4. Click "Invite users" → Enter `clearpathestate@gmail.com`
5. Check your email and set password
6. Go to `yoursite.netlify.app/admin` to log in

## That's it!

After this setup, you can edit your site at `/admin` and changes go live automatically.

---

**Need help?** Make sure all files from the GITHUB-UPLOAD folder are visible in your GitHub repository before connecting to Netlify.
