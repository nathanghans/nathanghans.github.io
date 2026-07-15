# How to Add Screenshots

## When you have your screenshots ready:

### Option 1: Simple replacement (recommended)

1. Find this code in `index.html` (appears 5 times):

```html
<div class="project-screenshot">
    <div class="placeholder-icon">📸</div>
    <div class="placeholder-label">PROJECTNAME</div>
    <div class="placeholder-hint">Replace with project screenshot</div>
</div>
```

2. Replace the entire `<div class="project-screenshot">...</div>` block with:

```html
<div class="project-screenshot">
    <img src="images/yourfile.png" alt="Project screenshot">
</div>
```

### Option 2: Using the GitHub web interface

1. Go to your repo on GitHub
2. Click into the `images/` folder
3. Click "Add file" → "Upload files"
4. Upload your 5 screenshots
5. Edit `index.html` through GitHub's web editor
6. Replace each placeholder as shown above

---

## Current Placeholders:

1. **SUBTRACTIONPRACTICE** (Slide 3)
2. **SPELLSPELL** (Slide 4)
3. **TESTWEBSITE** (Slide 5)
4. **TONEPICKER** (Slide 6)
5. **ORLANDOMAGIC** (Slide 7)

## Recommended image specs:

- **Format**: PNG or JPG
- **Dimensions**: 680px wide × 760px tall (or larger with same ratio)
- **File size**: Under 500KB each for fast loading
