# How to Add Your Own Photos to the Website

## Method 1: Using Image Hosting Services (Easiest)

### Step 1: Upload Photos to Imgur (Free)
1. Go to https://imgur.com
2. Click "New post" (you don't need an account)
3. Upload your photos
4. Right-click each image and select "Copy image address"

### Step 2: Replace Image URLs in Your HTML Files

For example, in `gallery.html`, find this line:
```html
<img src="https://images.unsplash.com/photo-1553284965-83fd3e82fa5a?w=600" alt="Dressage Training">
```

Replace the `src="..."` part with your Imgur link:
```html
<img src="YOUR_IMGUR_LINK_HERE" alt="Dressage Training">
```

### Step 3: Update These Files
- `gallery.html` - Replace all 8 gallery images
- `coaching.html` - Replace team member photos (5 photos)
- `index.html` - No photos to replace (uses background color)

## Method 2: Storing Photos in Your Repository (Better for long-term)

### Step 1: Create an Images Folder
1. In your GitHub repository, click "Add file" → "Create new file"
2. Type `images/placeholder.txt` and commit
3. This creates an "images" folder

### Step 2: Upload Photos to the Folder
1. Go into the `images` folder
2. Click "Add file" → "Upload files"
3. Upload all your photos
4. Name them something simple like: `coach-kelley.jpg`, `president-julia.jpg`, `gallery-1.jpg`, etc.

### Step 3: Update Image Paths in HTML
Change from:
```html
<img src="https://images.unsplash.com/..." alt="...">
```

To:
```html
<img src="images/your-photo-name.jpg" alt="...">
```

## Photos You Need

### For Gallery (gallery.html)
- 8 photos of team activities, shows, practices, etc.

### For Team Officials (coaching.html)
- Coach photo
- President photo  
- Vice President photo
- Treasurer photo
- Social Chair photo

## Image Size Recommendations
- Gallery photos: 600-800px wide
- Team member photos: 400-600px wide
- File format: JPG or PNG
- Keep file sizes under 500KB each for fast loading

## Example: Updating Gallery Photo

Find this in `gallery.html`:
```html
<div class="gallery-item">
    <img src="https://images.unsplash.com/photo-1553284965-83fd3e82fa5a?w=600" alt="Dressage Training">
</div>
```

Change to:
```html
<div class="gallery-item">
    <img src="images/our-team-at-show.jpg" alt="Our Team at Regional Show">
</div>
```

---

**Need Help?** If you get stuck, just let me know which part is confusing!
