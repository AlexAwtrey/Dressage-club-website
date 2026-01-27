# Auburn Dressage Club Website

A clean, professional website for the Auburn Dressage Club, affiliated with the Intercollegiate Dressage Association.

## Files Included

- `index.html` - Homepage
- `faqs.html` - Frequently Asked Questions
- `member-info.html` - Member Information
- `schedule.html` - Practice and Show Schedule
- `coaching.html` - Coaching Staff Information
- `gallery.html` - Photo Gallery
- `contact.html` - Contact Form
- `socials.html` - Social Media Links
- `styles.css` - All styling for the website

## How to Customize

### 1. Update Club Information

Search for `[INSERT` in all HTML files to find placeholder text that needs to be replaced with your actual information:

- Membership costs
- Practice days/times/location
- Show schedule and dates
- Coach names and bios
- Contact information
- Social media handles

### 2. Add Your Photos to Gallery

In `gallery.html`, replace the placeholder image URLs with your own:
- Upload photos to an image hosting service (Imgur, Google Photos, etc.)
- Replace the `src` URLs in the gallery items

### 3. Set Up Contact Form

The contact form uses Formspree (free for basic use):
1. Go to https://formspree.io
2. Sign up for a free account
3. Create a new form
4. Copy your form ID
5. In `contact.html`, replace `YOUR_FORM_ID` with your actual Formspree ID

### 4. Update Colors (Optional)

In `styles.css`, you can change the Auburn colors:
- `#03244d` - Auburn Navy Blue
- `#e87722` - Auburn Orange

## Deploying to Render

### Step 1: Create a GitHub Account & Repository

1. Go to https://github.com and create a free account (if you don't have one)
2. Click the "+" in the top right, select "New repository"
3. Name it something like "auburn-dressage-website"
4. Make it Public
5. Click "Create repository"

### Step 2: Upload Your Files to GitHub

**Option A: Using GitHub Web Interface (Easiest for beginners)**

1. On your repository page, click "uploading an existing file"
2. Drag and drop ALL the website files (HTML, CSS)
3. Scroll down and click "Commit changes"

**Option B: Using GitHub Desktop (Recommended for multiple updates)**

1. Download GitHub Desktop from https://desktop.github.com
2. Clone your repository to your computer
3. Copy all website files into the repository folder
4. In GitHub Desktop, write a commit message like "Initial website upload"
5. Click "Commit to main" then "Push origin"

### Step 3: Deploy on Render

1. Go to https://render.com and sign up for a free account
2. Click "New +" and select "Static Site"
3. Connect your GitHub account when prompted
4. Select your "auburn-dressage-website" repository
5. Configure the settings:
   - **Name:** auburn-dressage-club (or your preferred name)
   - **Branch:** main
   - **Build Command:** Leave blank
   - **Publish Directory:** Leave blank (or enter `.` if required)
6. Click "Create Static Site"

Render will deploy your site! It takes 1-2 minutes. You'll get a free URL like:
`https://auburn-dressage-club.onrender.com`

### Step 4: Updates

Whenever you want to update your website:
1. Edit the HTML files on your computer
2. Push changes to GitHub (using GitHub Desktop or web interface)
3. Render will automatically redeploy your site!

## Getting a Custom Domain (Optional)

You can purchase a custom domain (like auburnequestrian.com) from:
- Namecheap (~$10/year)
- Google Domains (~$12/year)
- GoDaddy (~$15/year)

Then in Render, go to Settings → Custom Domains to connect it.

## Need Help?

- **HTML/CSS Help:** https://www.w3schools.com
- **Render Documentation:** https://render.com/docs/static-sites
- **GitHub Help:** https://docs.github.com

## Site Colors

- Navy Blue: `#03244d` (Auburn University official color)
- Orange: `#e87722` (Auburn University official color)

## Browser Support

This site works on all modern browsers:
- Chrome, Firefox, Safari, Edge
- Mobile devices (responsive design)

---

Good luck with your Auburn Dressage Club website! 🐴
