# Personal Academic Website - Effiong Blessing U.

Professional academic portfolio website showcasing research in neuromorphic computing, publications, and achievements.

## 🚀 Live Website

Once deployed, your website will be available at: `https://YOUR-USERNAME.github.io`

## 📁 Files Included

- `index.html` - Main website structure
- `style.css` - Professional styling and responsive design
- `script.js` - Interactive features and smooth scrolling
- `README.md` - Setup instructions

## 🛠️ Setup Instructions

### Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** icon (top right) → **"New repository"**
3. **Repository name:** `YOUR-USERNAME.github.io` 
   - Replace `YOUR-USERNAME` with your actual GitHub username
   - Example: If your username is `blessingeffiong`, name it `blessingeffiong.github.io`
4. Set repository to **Public**
5. Click **"Create repository"**

### Step 2: Upload Website Files

**Option A: Upload via GitHub Website (Easiest)**

1. In your new repository, click **"uploading an existing file"**
2. Drag and drop these files:
   - `index.html`
   - `style.css`
   - `script.js`
   - `README.md`
3. Add commit message: "Initial website upload"
4. Click **"Commit changes"**

**Option B: Using Git Command Line**

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io
cd YOUR-USERNAME.github.io
# Copy the website files to this directory
git add .
git commit -m "Initial website upload"
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to repository **Settings** (top right)
2. Scroll to **"Pages"** section (left sidebar)
3. Under **"Source"**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **"Save"**
5. Wait 2-3 minutes for deployment

### Step 4: Access Your Website

Your website will be live at: `https://YOUR-USERNAME.github.io`

## ✏️ Customization Guide

### Update Personal Information

**In `index.html`:**

1. **Social Media Links** (Line ~370):
   ```html
   <a href="https://scholar.google.com/citations?user=YOUR_ID" ...>Google Scholar</a>
   <a href="https://www.linkedin.com/in/YOUR-PROFILE" ...>LinkedIn</a>
   <a href="https://github.com/YOUR-USERNAME" ...>GitHub</a>
   ```
   Replace with your actual profile URLs

2. **Email/Phone** (Line ~360):
   Update if needed

3. **Add Profile Photo** (Optional):
   - Upload image to repository
   - Add in hero section:
   ```html
   <img src="profile.jpg" alt="Effiong Blessing" class="profile-img">
   ```

### Add More Publications

In `index.html`, find the Publications section (~250) and add:

```html
<div class="pub-item">
    <h4>Your Publication Title</h4>
    <p class="pub-authors">Author List</p>
    <p class="pub-venue">Conference/Journal Name</p>
</div>
```

### Change Colors

In `style.css`, update color variables (Line ~12):

```css
:root {
    --primary-color: #1e40af;  /* Main blue */
    --secondary-color: #3b82f6;  /* Lighter blue */
    --accent-color: #60a5fa;  /* Accent blue */
}
```

## 🎨 Features

- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Smooth scrolling navigation
- ✅ Professional academic layout
- ✅ Publication showcase
- ✅ Research highlights
- ✅ Timeline for achievements
- ✅ Contact information
- ✅ SEO optimized
- ✅ Fast loading

## 📱 Mobile Responsive

Website automatically adapts to:
- Desktop (1200px+)
- Tablet (768px - 1200px)
- Mobile (< 768px)

## 🔧 Troubleshooting

**Website not showing after 5 minutes?**
1. Check Settings → Pages shows green checkmark
2. Verify files are in root directory (not in a folder)
3. Ensure repository is named `YOUR-USERNAME.github.io`
4. Clear browser cache (Ctrl+Shift+R)

**Changes not appearing?**
1. Wait 1-2 minutes after committing changes
2. Hard refresh browser (Ctrl+Shift+R)
3. Check GitHub Actions tab for build status

## 📊 Analytics (Optional)

Add Google Analytics:
1. Get tracking ID from [Google Analytics](https://analytics.google.com)
2. Add before `</head>` in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-ID');
</script>
```

## 🔒 Custom Domain (Optional)

To use custom domain (e.g., `www.blessingeffiong.com`):

1. Buy domain from registrar (Namecheap, GoDaddy, etc.)
2. In repository Settings → Pages → Custom domain
3. Enter your domain name
4. Update DNS records at your registrar:
   ```
   Type: A
   Host: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153
   
   Type: CNAME
   Host: www
   Value: YOUR-USERNAME.github.io
   ```

## 📞 Support

For issues:
1. Check [GitHub Pages documentation](https://docs.github.com/en/pages)
2. Verify all files uploaded correctly
3. Check browser console for errors (F12)

## 📄 License

This website template is provided as-is for personal academic use.

---

**Created for:** Effiong Blessing U.  
**Institution:** Saint Louis University  
**Research:** Neuromorphic Computing | Project Phasor  
**Year:** 2026
