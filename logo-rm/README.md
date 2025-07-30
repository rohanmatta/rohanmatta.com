# R.M. Logo Options

This folder contains different logo styles for "R.M." (Rohan Matta) that you can use to replace the current "A.F." logo.

## Logo Styles Available:

### 1. Gradient Circle (Recommended)
- Purple gradient background
- Circular shape
- Hover effects
- Matches your website's color scheme

### 2. Minimal Circle
- Solid purple background
- Clean, simple design
- Subtle hover effects

### 3. Square Version
- Rounded square design
- Professional look
- Good for modern portfolios

### 4. Simple Text
- Just text, no background
- Clean and minimal

## How to Integrate:

### Option A: Replace the image logo
1. Open `logo.html` in your browser to see all options
2. Choose your preferred style
3. Copy the CSS for that style
4. Replace the logo image in `index.html` with the text-based version

### Option B: Keep both options
- You can test the text logo while keeping the image logo as backup

## To Delete This Folder:
```bash
rm -rf logo-rm
```

## CSS Classes to Copy:

**Gradient Circle (Recommended):**
```css
.rm-logo {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 50px;
    height: 50px;
    background: linear-gradient(135deg, #684FFF 0%, #8B5CF6 100%);
    border-radius: 50%;
    color: white;
    font-family: 'Arial', sans-serif;
    font-weight: bold;
    font-size: 18px;
    text-decoration: none;
    transition: all 0.3s ease;
    box-shadow: 0 2px 10px rgba(104, 79, 255, 0.3);
}

.rm-logo:hover {
    transform: scale(1.05);
    box-shadow: 0 4px 15px rgba(104, 79, 255, 0.4);
}
```

**HTML to replace the logo:**
```html
<a href="#" class="rm-logo">R.M.</a>
``` 