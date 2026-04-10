# 🎨 PortSuite — Professional Portfolio Builder

**Build. Customize. Deploy. For free, forever.**

A modern, zero-backend portfolio builder that generates pure HTML/CSS/JS portfolios. Create a professional portfolio in minutes, customize it with 9 beautiful themes, and deploy to GitHub Pages with zero coding required.

## ✨ Features

- **9 Beautiful Themes** - Midnight, Arctic, Forest, Crimson, Sand, Slate, Rose, Obsidian, Ocean
- **Zero Dependencies** - Pure HTML, CSS, and JavaScript (no backend needed)
- **Mobile Responsive** - Looks perfect on all devices
- **GitHub Pages Ready** - Deploy instantly to your own domain
- **Easy Customization** - Change colors, fonts, and layout with live preview
- **Download & Host Anywhere** - Get a ZIP of your portfolio files
- **No Vendor Lock-in** - Your portfolio is yours alone

## 🚀 Quick Start

### 1. Open PortSuite Builder
Open `portsuite.html` in your web browser. This is your portfolio builder interface.

### 2. Fill in Your Information
- **Personal Section**: Name, title, location, contact info
- **Experience**: Add your work history
- **Education**: Add your academic background
- **Projects**: Showcase your best work
- **Skills**: List your technical skills
- **Gallery**: Add your portfolio images
- **Blog Posts**: Write about your expertise
- **Contact & Social Links**: Email, LinkedIn, GitHub, Twitter, etc.

### 3. Customize Design
- **Choose Theme**: Pick from 9 color themes
- **Select Font**: Choose typography
- **Photo Style**: Select how your profile photo appears
- **Navbar Style**: Classic, Minimal, or Sidebar navigation
- **Section Visibility**: Show/hide sections like research, awards, certifications

### 4. Download Your Portfolio
Click "Download Portfolio" to get:
- `index.html` - Your live portfolio
- `data.json` - Your portfolio content
- `styles.css` - Theme and colors
- `README.md` - Quick reference guide

### 5. Deploy to GitHub Pages (Free!)

#### Option A: Terminal Method (Recommended for Beginners)
1. **Install Git**: Download from [git-scm.com](https://git-scm.com/download)
2. **Create GitHub Account**: Sign up at [github.com](https://github.com)
3. **Create Repository**:
   - Click `+` → New Repository
   - Name: `YOUR-USERNAME.github.io` (replace YOUR-USERNAME)
   - Set to **Public**
   - ❌ Do NOT check "Add a README file"
   - Click Create

4. **Generate GitHub Token**:
   - Go to github.com/settings/tokens
   - Click "Generate new token (classic)"
   - Name: "Portfolio Upload"
   - Check only: `repo`
   - Click "Generate token"
   - **Copy the token and save it safety** (you won't see it again!)

5. **Upload Files via Terminal**:
   ```bash
   cd Desktop/YOUR-PORTFOLIO-FOLDER
   git clone https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
   cd YOUR-USERNAME.github.io
   cp -r ../YOUR-PORTFOLIO-FOLDER/* .
   git config --global user.name "Your Name"
   git config --global user.email "your@email.com"
   git branch -M main
   git add .
   git commit -m "Upload portfolio"
   git push -u origin main
   ```
   *(When prompted for password, paste your GitHub token)*

6. **Done!** 
   - Wait 2-3 minutes
   - Visit `https://YOUR-USERNAME.github.io`
   - Your portfolio is live! 🎉

#### Option B: Browser Upload Method
1. Create `YOUR-USERNAME.github.io` repository on GitHub
2. Click "Add file" → "Upload files"
3. Drag your portfolio files into the upload area
4. Click "Commit changes"
5. Go to Settings → Pages → Enable GitHub Pages
6. Visit `https://YOUR-USERNAME.github.io`

## 📁 File Structure

```
backup/
├── portsuite.html          ← The portfolio builder (open this!)
├── data.json               ← Sample portfolio data
├── README.md               ← This file
└── .gitignore              ← Git configuration
```

## 🎨 Customization

### Edit Portfolio Later
1. Open `data.json` in a text editor
2. Edit your content (name, experience, projects, etc.)
3. Save the file
4. Refresh your portfolio in the browser

### Themes Available
- **Midnight** - Dark blue with cyberpunk vibes
- **Arctic** - Cool blues and whites
- **Forest** - Green nature-inspired
- **Crimson** - Bold reds and burgundy
- **Sand** - Warm beige and gold
- **Slate** - Professional purple-blue
- **Rose** - Elegant pink tones
- **Obsidian** - Minimal dark gray
- **Ocean** - Deep ocean blues

### Fonts Supported
Multiple font families including DM Sans, Syne, Inter, Poppins, Quicksand, and more.

## 🔒 Data & Privacy

- ✅ **No Backend Server** - Everything runs locally in your browser
- ✅ **No Data Collection** - We don't store your information
- ✅ **Your Data, Your Control** - You own everything
- ✅ **Open Source** - Pure HTML/CSS/JS you can inspect

## ⚡ Performance

- **Zero Database Queries** - Instant load times
- **Tiny File Size** - Portfolio loads in milliseconds
- **SEO Friendly** - Your portfolio ranks in Google
- **Works Offline** - View your portfolio even without internet

## 🚀 Advanced: Custom Domain

If you want a custom domain (like `yourname.com`):

1. Buy domain from GoDaddy, Namecheap, etc.
2. Point domain DNS to GitHub Pages:
   - CNAME: YOUR-USERNAME.github.io
   - Or A records to GitHub IP addresses
3. Add domain in repo Settings → Pages → Custom domain

## 📝 Sections Available

**Core**
- Hero section (name, title, photo)
- Experience & Education
- Skills & Social Links

**Optional**
- Projects & Portfolio
- Blog Posts
- Gallery
- Research & Publications
- Awards & Certifications
- Languages
- Hobbies

Toggle any section on/off in the builder's Design tab.

## 🐛 Troubleshooting

**Portfolio not showing?**
- Check GitHub Pages is enabled in repo Settings
- Wait 2-3 minutes after pushing
- Clear browser cache (Ctrl+Shift+Delete)

**Changes not appearing?**
- Edit `data.json` directly
- Run `git add .` → `git commit -m "Update"` → `git push`
- Hard refresh browser (Ctrl+F5)

**Large media files?**
- GitHub doesn't allow files >100MB
- Upload videos to YouTube and embed
- Host large images on Google Drive or Imgur

## 📧 Support

For issues or questions:
1. Check the troubleshooting section above
2. Review `data.json` structure
3. Ensure all required fields are filled

## 📄 License

Built with ♥ for creators. Host anywhere, anytime.

---

**Ready to build?** Open `portsuite.html` and start creating your professional portfolio! 🚀

**Admin.html won't let me login**


- **GitHub Docs**: https://pages.github.com
- **GitHub API**: https://docs.github.com/rest
- **Questions**: Check browser console (F12) for errors

---

**That's it!** Your portfolio is now live, version-controlled, and editable. No backend. No server. Just GitHub. 🎉
