# LinkShort URL Shortener

A modern, beautiful URL shortener built with pure HTML, CSS, and JavaScript.

## 🚀 Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy)

### Quick Deploy Steps:

1. **Fork or Upload** this repository to your GitHub account
2. **Connect to Netlify**: 
   - Go to [Netlify](https://netlify.com)
   - Click "Add new site" → "Import an existing project"
   - Connect your GitHub account
   - Select this repository
3. **Deploy**: Click "Deploy site" (no build settings needed!)
4. Your site will be live at `https://your-site-name.netlify.app`

## 🌐 Deploy to Other Platforms

### Vercel
```bash
npm i -g vercel
vercel
```

### GitHub Pages
1. Go to repository Settings → Pages
2. Select branch: `main`
3. Select folder: `/ (root)`
4. Click Save

### Cloudflare Pages
1. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
2. Create a new project
3. Connect your Git repository
4. Build settings: None needed (static site)
5. Deploy!

## ✨ Features

- 🔗 **URL Shortening** - Multiple API support with fallback
- 📱 **QR Code Generation** - Automatic for every link
- 📊 **Analytics** - Track clicks, devices, locations
- ✏️ **Custom Slugs** - Create branded short links
- 🎨 **Beautiful UI** - Modern iOS-inspired dark theme
- 💾 **Auto-Save** - Links persist in browser storage
- 🆓 **100% Free** - No limits, no tracking

## 📁 File Structure

```
.
├── index.html       # Main HTML file
├── style.css        # All styling
├── script.js        # All JavaScript
├── netlify.toml     # Netlify configuration
├── vercel.json      # Vercel configuration (optional)
└── README.md        # This file
```

## 🛠️ Local Development

No build process needed! Just open `index.html` in your browser.

For a better development experience with live reload:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000`

## 🔧 Configuration

### Custom Domain (for Netlify/Vercel)

1. Add your custom domain in platform settings
2. Update DNS records as instructed
3. Your short links will use your custom domain!

### API Keys (Optional)

The app uses free APIs by default:
- TinyURL
- is.gd
- v.gd
- Shrtco.de

No API keys required!

## 📝 Browser Compatibility

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers

## 🤝 Contributing

Feel free to open issues or submit pull requests!

## 📄 License

MIT License - feel free to use for personal or commercial projects.

## 👨‍💻 Developer

Created by **Saimum Arafat**

- GitHub: [@saimumarafat](https://github.com/saimumarafat)
- LinkedIn: [saimumarafat](https://linkedin.com/in/saimumarafat)
- Email: saimumcodes@gmail.com

## 🌟 Support

If you find this useful, please star the repository!
