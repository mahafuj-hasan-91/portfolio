# Portfolio Website

A modern, cyberpunk-themed portfolio website for Computer Science students and developers.

## 🚀 Features

- **Cyberpunk Design** - Bold, futuristic aesthetic with animated grid background
- **Responsive Layout** - Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations** - Eye-catching scroll animations and hover effects
- **Interactive Elements** - Glowing cursor effect and dynamic UI components
- **SEO Optimized** - Meta tags and semantic HTML structure
- **Fast Loading** - Optimized CSS and vanilla JavaScript

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── style.css           # All styling
├── script.js           # Interactive functionality
├── assets/             # Assets folder
│   └── images/         # Store your images here
├── README.md           # This file
└── CNAME              # Custom domain configuration (optional)
```

## 🛠️ Customization Guide

### 1. Personal Information

**Update the following in `index.html`:**

- **Name**: Replace "Alex Chen" with your name
- **Meta Tags**: Update description and keywords in `<head>`
- **Hero Section**: Modify the tagline and description
- **Skills**: Update skill cards with your technologies
- **Projects**: Replace project descriptions and links
- **Social Links**: Update all social media URLs and email

### 2. Colors & Theme

**Modify CSS variables in `style.css`:**

```css
:root {
    --bg-primary: #0a0e27;        /* Main background */
    --bg-secondary: #111633;      /* Card backgrounds */
    --accent-cyan: #00fff5;       /* Primary accent */
    --accent-pink: #ff006e;       /* Secondary accent */
    --accent-purple: #8338ec;     /* Tertiary accent */
}
```

### 3. Adding Images

Place your images in the `assets/images/` folder:

- `favicon.png` - Browser tab icon (32x32px or 64x64px)
- Project screenshots (optional)
- Profile photo (optional)

Update image paths in HTML:
```html
<link rel="icon" type="image/png" href="assets/images/favicon.png">
```

### 4. GitHub Links

Replace placeholder GitHub links with your repositories:
```html
<a href="https://github.com/yourusername/project-name" target="_blank">
```

## 🌐 Deployment to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `yourusername.github.io` (replace with your GitHub username)
3. Make it **public**
4. Don't initialize with README (you already have one)

### Step 2: Upload Your Files

**Option A: Using Git Command Line**

```bash
# Navigate to your portfolio folder
cd portfolio-website

# Initialize git repository
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial commit - Portfolio website"

# Add remote repository
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Option B: Using GitHub Desktop**

1. Open GitHub Desktop
2. File → Add Local Repository
3. Choose your portfolio folder
4. Publish repository to GitHub

**Option C: Upload via GitHub Website**

1. Go to your repository on GitHub
2. Click "uploading an existing file"
3. Drag and drop all your files
4. Commit changes

### Step 3: Enable GitHub Pages

1. Go to repository **Settings**
2. Scroll to **Pages** section (left sidebar)
3. Under **Source**, select `main` branch
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io`

## 🌍 Adding a Custom Domain

### Step 1: Purchase a Domain

Buy a domain from providers like:
- Namecheap
- GoDaddy
- Google Domains
- Cloudflare

### Step 2: Configure DNS Records

Add these DNS records in your domain provider's dashboard:

```
Type: A
Name: @
Value: 185.199.108.153

Type: A
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153

Type: CNAME
Name: www
Value: yourusername.github.io
```

### Step 3: Add CNAME File

Create a file named `CNAME` (no extension) in your repository root:

```
yourdomain.com
```

### Step 4: Configure in GitHub

1. Go to repository **Settings** → **Pages**
2. Enter your custom domain in **Custom domain** field
3. Click **Save**
4. Wait 24-48 hours for DNS propagation
5. Enable **Enforce HTTPS** once available

## 🔧 Local Development

To test locally before deploying:

1. Open `index.html` in your browser directly, or
2. Use a local server (recommended):

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (install live-server globally)
npm install -g live-server
live-server
```

Then open `http://localhost:8000` in your browser.

## 📝 Best Practices

1. **Test on Multiple Devices** - Check responsive design on phone, tablet, desktop
2. **Optimize Images** - Compress images before uploading (use TinyPNG, ImageOptim)
3. **Update Regularly** - Keep projects and skills current
4. **Add Analytics** - Consider Google Analytics to track visitors
5. **SEO** - Update meta descriptions and titles for better search ranking

## 🐛 Troubleshooting

**Site not loading:**
- Wait 5-10 minutes after first deployment
- Check that repository is public
- Verify GitHub Pages is enabled

**Custom domain not working:**
- DNS changes take 24-48 hours
- Double-check DNS records
- Ensure CNAME file has correct domain

**Animations not working:**
- Clear browser cache
- Check browser console for errors
- Ensure JavaScript is enabled

## 📄 License

Feel free to use this template for your personal portfolio. Attribution appreciated but not required.

## 🤝 Contributing

Found a bug or want to improve the template? Feel free to:
1. Fork the repository
2. Create your feature branch
3. Submit a pull request

## 📧 Contact

If you have questions or need help with customization, feel free to reach out!

---

**Built with ❤️ and ⚡**

Good luck with your portfolio! 🚀