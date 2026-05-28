# 🚀 DEPLOYMENT GUIDE - Hapjesfestival Website

## For Non-Technical Users - Step by Step

---

## 📋 QUICK START - NETLIFY DROP (5 minutes)

This is the **easiest and fastest** way to get your website online.

### What you need:
- ✅ The `hapjesfestival-website` folder on your computer
- ✅ An internet connection
- ✅ A web browser (Chrome, Firefox, Safari, Edge)

### Steps:

#### 1. Open Netlify Drop
1. Open your web browser
2. Go to: **https://drop.netlify.com**
3. You'll see a large area with the text "Drag a folder with an index.html here"

#### 2. Drag the Website Folder
1. Open the `hapjesfestival-website` folder on your computer
2. Drag the **entire folder** to the Netlify Drop window
   - OR: Click on the field and select the folder
3. Wait 10-30 seconds while the website is uploaded

#### 3. Your Website is Live!
1. You'll get a URL like: `happy-hapjes-xyz.netlify.app`
2. Click on the URL to view your website
3. **IMPORTANT**: Copy and save this URL!

#### 4. Customize URL (Optional but recommended)
1. Click the **"Claim this site"** button (at the top of the page)
2. Create a free Netlify account:
   - Use your email address
   - Or log in with GitHub/Google
3. After logging in:
   - Go to **Site Settings**
   - Click on **"Change site name"**
   - Enter: `hapjesfestival` or `hkkfestival`
   - Your new URL: `hapjesfestival.netlify.app`

✅ **DONE! Your website is now online.**

---

## 🔄 Updating Website (after changes)

### On Netlify:
1. Log in to **netlify.com**
2. Click on your site (`hapjesfestival`)
3. Go to **Deploys** tab
4. Drag the new version of your folder to "Need to update your site?"
5. Wait 10 seconds - done!

**OR via Netlify Drop:**
1. Go to **drop.netlify.com** again
2. Drag your updated folder
3. You'll get a new URL
4. The old URL will also keep working if you want to keep it

---

## 📱 ALTERNATIVE 1 - GITHUB PAGES

**A bit more technical but with version control.**

### Preparation:
1. Create a free account on **github.com**
2. Confirm your email address

### Deployment Steps:

#### Step 1: Create Repository
1. Log in to GitHub
2. Click on **"+"** in top right → **"New repository"**
3. Repository name: `hapjesfestival`
4. Select **"Public"**
5. ❌ DO NOT check: "Add a README file"
6. Click **"Create repository"**

#### Step 2: Upload Files
1. You'll now see an empty repository page
2. Click on **"uploading an existing file"**
3. Drag ALL files from your `hapjesfestival-website` folder:
   - `index.html`
   - `styles.css`
   - `script.js`
   - The entire `images` folder
4. Scroll down
5. Click **"Commit changes"**
6. Wait for upload to complete

#### Step 3: Enable GitHub Pages
1. Click on **"Settings"** at the top (gear icon)
2. Scroll in the left menu to **"Pages"**
3. Under "Source":
   - Select **"Deploy from a branch"**
4. Under "Branch":
   - Select **"main"**
   - Select **"/ (root)"**
5. Click **"Save"**

#### Step 4: Wait for Deployment
1. Refresh the page after 1-2 minutes
2. At the top you'll see: **"Your site is live at..."**
3. Your URL: `yourusername.github.io/hapjesfestival`

### Making Updates:
1. Go to your repository on GitHub
2. Click on the file you want to edit
3. Click on the pencil icon (Edit)
4. Make your changes
5. Scroll down and click **"Commit changes"**
6. After 1-2 minutes your website is updated

---

## ⚡ ALTERNATIVE 2 - VERCEL

**Fast and professional with good performance.**

### Steps:

#### 1. Create Account
1. Go to **vercel.com**
2. Click on **"Sign Up"**
3. Choose **"Continue with GitHub"** or use your email
4. Confirm your account

#### 2. Upload Project
1. Click on **"Add New..."** (top right)
2. Select **"Project"**
3. Click on **"Browse"** or drag the `hapjesfestival-website` folder
4. Wait for upload to complete

#### 3. Deploy Settings
1. Project Name: `hapjesfestival`
2. Framework Preset: **"Other"**
3. Leave the rest as default
4. Click **"Deploy"**

#### 4. Website Live!
1. After 30-60 seconds your website is live
2. Your URL: `hapjesfestival.vercel.app`
3. Click on **"Visit"** to view

### Making Updates:
1. Log in to Vercel
2. Go to your project
3. Click on **"Upload"** (at the top)
4. Drag your new files
5. Automatic deployment starts

---

## 🎯 WHICH OPTION TO CHOOSE?

| Option | Difficulty | Update Process | Best For |
|--------|------------|----------------|----------|
| **Netlify Drop** | ⭐ Very easy | Very simple | Beginners, one-time use |
| **GitHub Pages** | ⭐⭐ Medium | Simple via interface | People who want version control |
| **Vercel** | ⭐⭐ Medium | Simple via interface | Speed and performance |

**🏆 RECOMMENDATION**: Start with **Netlify Drop** - you can always switch later!

---

## 📊 AFTER DEPLOYMENT - CHECKLIST

After going online, test these things:

### ✅ Functional Test:
- [ ] Website opens correctly
- [ ] All images load
- [ ] Countdown timer works
- [ ] Navigation menu works (also on mobile)
- [ ] WhatsApp link opens correctly
- [ ] Email link works
- [ ] Social sharing buttons work
- [ ] Scroll to top button appears when scrolling
- [ ] Smooth scrolling works
- [ ] Online shop link works (opens inkudelstaart.nl/shop)

### ✅ Responsive Test:
Test on different devices:
- [ ] Desktop computer (large screen)
- [ ] Laptop
- [ ] Tablet
- [ ] Smartphone (iPhone/Android)

**Handy tool**: Open your website and press **F12** → click on phone icon for mobile preview

### ✅ Performance Test:
1. Go to **https://pagespeed.web.dev**
2. Enter your URL
3. Aim for score >90 for mobile and desktop

### ✅ Browser Test:
Test in different browsers:
- [ ] Google Chrome
- [ ] Safari
- [ ] Firefox
- [ ] Microsoft Edge

---

## 🔗 SHARING YOUR URL

### Creating a Short URL (Optional):
If your URL is too long, create a short version:

1. Go to **bitly.com** or **tinyurl.com**
2. Paste your long URL
3. Click "Shorten"
4. Get a short URL like: `bit.ly/hapjesfestival2026`

### Creating a QR Code:
For flyers and posters:
1. Go to **qr-code-generator.com**
2. Select "URL"
3. Paste your website URL
4. Download the QR code
5. Print on your promotional materials

---

## 🗑️ DELETING WEBSITE (after the event)

### Netlify:
1. Log in to **netlify.com**
2. Go to your site
3. Click on **Settings**
4. Scroll all the way down
5. Click **"Delete site"**
6. Type the site name to confirm
7. Click **"Delete"**

### GitHub Pages:
1. Log in to **github.com**
2. Go to the repository
3. Click on **Settings**
4. Scroll all the way down to "Danger Zone"
5. Click **"Delete this repository"**
6. Type the repository name to confirm
7. Click **"I understand, delete this repository"**

### Vercel:
1. Log in to **vercel.com**
2. Go to your project
3. Click on **Settings**
4. Scroll down to "Delete Project"
5. Click **"Delete"**
6. Type the project name
7. Click **"Delete"**

**💡 TIP**: You can also just leave the website online - it costs nothing!

---

## ❓ FREQUENTLY ASKED QUESTIONS

### Q: Does it cost money to put the website online?
**A**: No! All three options are 100% free for this type of website.

### Q: How long does deployment take?
**A**: 
- Netlify Drop: 10-30 seconds
- GitHub Pages: 1-3 minutes
- Vercel: 30-60 seconds

### Q: Can I change the website later?
**A**: Yes! You can always make changes and re-upload.

### Q: What if my images don't load?
**A**: 
1. Check if the `images` folder was uploaded
2. Verify that filenames match exactly (case-sensitive!)
3. Check if images aren't too large (max 5MB per file)

### Q: How long will the website stay online?
**A**: 
- Netlify/Vercel: Forever (or until you delete it)
- GitHub Pages: Forever (as long as the repository exists)

### Q: Can I use my own domain name (e.g. hapjesfestival.nl)?
**A**: Yes, but that costs money (~€10/year). For a temporary event, the free subdomain is sufficient!

### Q: Does the website work in other languages?
**A**: The current version is in Dutch. You can change all text in `index.html` to any language.

### Q: How many visitors can the website handle?
**A**: Thousands per day without problems. These hosting platforms are very scalable.

---

## 🆘 NEED HELP?

### Deployment not working?
1. **Netlify Drop not working**:
   - Check internet connection
   - Try another browser
   - Create account and use dashboard upload

2. **GitHub Pages not working**:
   - Wait 5 minutes and try again
   - Check if `index.html` is in the root (not in a subfolder)
   - Verify repository is "Public"

3. **Vercel not working**:
   - Try logging in again
   - Clear browser cache
   - Try another browser

### Website not working properly?
1. Open browser console (press **F12**)
2. Look for red error messages
3. Send this information to: **info@inkudelstaart.nl**

### Other problems?
Email: **info@inkudelstaart.nl**
WhatsApp: **06-16067577**

---

## 🎉 SUCCESS!

You're now ready to put your Hapjesfestival website online!

**Don't forget**:
1. Test thoroughly before sharing the URL
2. Save your login credentials securely
3. Share the URL on social media
4. Add the URL to your promotional materials

**Good luck with the event! 🍜✨**

---

_Last updated: May 2026_
