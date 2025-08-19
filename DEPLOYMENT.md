# Railway Deployment Guide

This guide will help you deploy the modernized Rosie's Frozen Yogurt website to Railway.

## Prerequisites

1. A [Railway](https://railway.app) account
2. A GitHub repository with this code
3. Node.js 14+ (already configured in `package.json`)

## Deployment Steps

### Option 1: GitHub Integration (Recommended)

1. **Push to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Modernized Rosie's website"
   git branch -M main
   git remote add origin https://github.com/yourusername/rosies-frozen-yogurt.git
   git push -u origin main
   ```

2. **Deploy on Railway**:
   - Visit [railway.app](https://railway.app)
   - Click "Start a New Project"
   - Select "Deploy from GitHub repo"
   - Choose your `rosies-frozen-yogurt` repository
   - Railway will automatically detect the Node.js project

3. **Automatic Configuration**:
   - Railway will read `package.json` and run `npm install`
   - It will use the `start` script: `http-server -p $PORT -a 0.0.0.0`
   - The site will be available at your Railway domain

### Option 2: Railway CLI

1. **Install Railway CLI**:
   ```bash
   npm install -g @railway/cli
   ```

2. **Login and Deploy**:
   ```bash
   railway login
   railway init
   railway up
   ```

### Option 3: Manual Upload

1. **Create ZIP file** with all project files
2. **Upload to Railway** through their dashboard
3. **Configure build/start commands** if needed

## Environment Variables

No environment variables are required for this static site deployment.

## Custom Domain (Optional)

1. In Railway dashboard, go to your project
2. Click on "Settings"
3. Add your custom domain (e.g., `rosiesofmv.com`)
4. Update your DNS records as instructed

## Post-Deployment Checklist

- ✅ Site loads correctly
- ✅ All sections display properly
- ✅ Navigation works (including mobile hamburger menu)
- ✅ Contact form appears correctly
- ✅ Responsive design functions on all devices
- ✅ Smooth scrolling works
- ✅ Animations and hover effects function

## Troubleshooting

### Common Issues:

**Build fails**: 
- Ensure `package.json` is in the root directory
- Check Node.js version compatibility

**Site doesn't load**:
- Verify the start script in `package.json`
- Check Railway logs for errors

**Missing files**:
- Ensure all files (`index.html`, `styles.css`, `script.js`) are in the repository

## Performance

The optimized website features:
- Fast loading times with minimal dependencies
- Efficient CSS with modern features
- Optimized JavaScript with debounced scroll handlers
- Mobile-first responsive design

## Support

For Railway-specific issues, consult:
- [Railway Documentation](https://docs.railway.app)
- [Railway Discord Community](https://discord.gg/railway)

For website issues, check the console logs and ensure all files are properly linked.

---

🍦 **Your modern Rosie's website is ready to serve Martha's Vineyard!**