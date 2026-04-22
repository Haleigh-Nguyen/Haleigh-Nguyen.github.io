# Your Portfolio — GitHub Pages

## File structure

```
your-repo/
├── index.html          ← Homepage / portfolio
├── travel.html         ← Travel log
├── art.html            ← Art & creativity gallery
├── interests.html      ← General interests
├── resume.pdf          ← Drop your resume here
└── images/
    ├── headshot.jpg            ← Your headshot (referenced in index.html)
    ├── product-prodigy-team.jpg
    ├── travel/
    │   ├── trip1-main.jpg
    │   ├── trip1-b.jpg
    │   ├── trip1-c.jpg
    │   └── place1.jpg, place2.jpg, place3.jpg ...
    └── art/
        ├── piece1.jpg through piece6.jpg
        └── wip1.jpg through wip5.jpg
```

## Deploying to GitHub Pages

1. Create a repo named `yourusername.github.io`
2. Upload all files (maintain the folder structure above)
3. Go to Settings → Pages → Source → main branch → Save
4. Live at https://yourusername.github.io in ~60 seconds

## What to customize

### index.html
- Replace `Your Name` and `YN` with your actual name/initials
- Update graduation year: `UT Austin '2X`
- Add your email, LinkedIn, GitHub links
- Update Product Prodigy website URL
- Add real photos to the `images/` folder

### travel.html
- Update the stats bar (cities, states, countries)
- Replace destination placeholders with real trips
- Add your actual travel photos

### art.html
- Swap placeholder items with your real creative work
- Update categories to match what you actually make
- The filter tabs work out of the box — just keep `data-category` attributes accurate

### interests.html
- Fill in the music, books, food, and other sections with real picks
- Update the "Currently" section regularly — it's a nice personal touch
- The Houston food section is a good conversation starter — fill it in!

## Adding photos

All image paths are relative. Just create the `images/` folder in the same directory as your HTML files and drop photos in. Supported formats: jpg, png, webp.

Each `<img>` tag has an `onerror` fallback so the page looks fine even with missing photos during development.
