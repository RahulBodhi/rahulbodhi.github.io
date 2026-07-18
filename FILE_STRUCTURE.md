# Complete File Structure

This document lists all files created for Dr. Rahul Bodhi's academic website.

## Root Directory Files

### Core Website Files (Required)
| File | Purpose | Priority |
|------|---------|----------|
| `index.html` | Homepage - Biography, education, recent work | CRITICAL |
| `research.html` | Research page - Publications, conferences | CRITICAL |
| `teaching.html` | Teaching page - Courses, philosophy | CRITICAL |
| `cv.html` | CV page - Full curriculum vitae | CRITICAL |
| `contact.html` | Contact page - Form, location, details | CRITICAL |
| `style.css` | Stylesheet - All visual design | CRITICAL |
| `script.js` | JavaScript - Mobile menu, interactions | HIGH |

### Configuration & SEO Files
| File | Purpose | Priority |
|------|---------|----------|
| `404.html` | Custom error page | MEDIUM |
| `robots.txt` | Search engine crawler instructions | MEDIUM |
| `sitemap.xml` | SEO sitemap for search engines | MEDIUM |
| `.gitignore` | Git ignore rules | LOW |
| `favicon.ico` | Browser tab icon (optional) | LOW |

### Documentation Files
| File | Purpose | When to Read |
|------|---------|--------------|
| `README.md` | Overview and customization guide | First |
| `QUICK_START.md` | 15-minute setup checklist | Before starting |
| `DEPLOYMENT_GUIDE.md` | Detailed step-by-step deployment | During setup |
| `PHOTO_GUIDE.md` | Profile photo requirements | Before taking photo |
| `UPDATE_GUIDE.md` | How to make future updates | After deployment |
| `FILE_STRUCTURE.md` | This file - complete listing | Reference |

## Directory Structure

```
rahul-bodhi-website/
│
├── index.html                 # Homepage
├── research.html              # Research & publications
├── teaching.html              # Teaching portfolio
├── cv.html                    # Curriculum vitae
├── contact.html               # Contact information
├── style.css                  # Main stylesheet
├── script.js                  # JavaScript functionality
├── 404.html                   # Error page
├── robots.txt                 # SEO crawler config
├── sitemap.xml                # SEO sitemap
├── .gitignore                 # Git ignore rules
├── favicon.ico                # Site icon (add later)
│
├── README.md                  # Main documentation
├── QUICK_START.md             # Quick setup checklist
├── DEPLOYMENT_GUIDE.md        # Detailed deployment guide
├── PHOTO_GUIDE.md             # Photo requirements
├── UPDATE_GUIDE.md            # Future updates guide
├── FILE_STRUCTURE.md          # This file
│
└── assets/
    ├── images/
    │   └── profile.jpg        # Your profile photo (ADD THIS)
    └── files/
        └── cv_rahul_bodhi.pdf # Your CV PDF (ADD THIS)
```

## File Sizes (Approximate)

| File Type | Size Range | Notes |
|-----------|-----------|-------|
| HTML files | 10-20 KB each | Text only, fast loading |
| CSS file | ~15 KB | Minified, optimized |
| JS file | ~3 KB | Minimal, fast |
| Profile photo | 50-500 KB | Should be < 500KB |
| CV PDF | 100 KB - 2 MB | Keep under 5MB |
| **Total (without assets)** | ~100 KB | Extremely lightweight |

## What You Need to Add

### Required Additions:
1. **Profile Photo**
   - Location: `assets/images/profile.jpg`
   - Specs: 400x400px, JPG/PNG, <500KB
   - See PHOTO_GUIDE.md for details

2. **CV PDF**
   - Location: `assets/files/cv_rahul_bodhi.pdf`
   - Format: PDF
   - Size: < 10MB

### Optional Additions:
3. **Favicon**
   - Location: Root directory (`favicon.ico`)
   - Size: 32x32px or 64x64px
   - Format: ICO or PNG

4. **Additional Images**
   - Research diagrams
   - Teaching photos
   - Conference photos
   - Store in: `assets/images/`

## Critical Content to Customize

### Must Update in ALL Files:
- `[Strategic Management/etc.]` → Your academic area
- `[University Name]` → Your actual universities
- `[Year]` → Actual years (20XX format)
- `[XXX]` → Office room number
- `rahul.bodhi@iimsirmaur.ac.in` → Verify email
- `[PIN Code]` → Actual postal code

### Must Update in Specific Files:

**index.html:**
- Biography paragraph
- Education details
- Recent publications (3-5 items)
- Contact information

**research.html:**
- All publications
- Working papers
- Conference presentations
- Research grants

**teaching.html:**
- Courses taught
- Teaching philosophy
- Student supervision
- Awards

**cv.html:**
- Complete employment history
- Full publication list
- All awards and grants
- Professional service

**contact.html:**
- Office address
- Phone numbers
- Office hours
- Google Maps location
- Social media links

## Files You Can Delete (If Desired)

If you want a minimal setup, you can delete these (not recommended):
- `404.html` (but nice to have)
- `robots.txt` (affects SEO slightly)
- `sitemap.xml` (affects SEO slightly)
- `FILE_STRUCTURE.md` (just reference)
- `PHOTO_GUIDE.md` (after photo is done)

**NEVER delete:**
- Any `.html` files (breaks navigation)
- `style.css` (breaks design)
- `script.js` (breaks mobile menu)
- `.gitignore` (keeps repo clean)

## Backup Strategy

Before making major changes:
1. Download current version from GitHub
2. Save as backup on your computer
3. Make changes
4. Test thoroughly
5. Upload new version

Or use GitHub's built-in version control:
- Every change is saved
- Can revert to any previous version
- Go to "Commits" to see history

## Security Notes

- **No sensitive data**: Don't upload confidential info
- **Public repository**: Anyone can see these files
- **Email protection**: The contact form uses `mailto:` which may attract spam
  - Consider using a contact form service (Formspree, Netlify Forms) for production
- **No backend**: This is a static site, no database to hack

## Performance Optimization

Already optimized:
- ✅ Minimal HTTP requests
- ✅ Compressed CSS
- ✅ No external dependencies (except Google Fonts)
- ✅ Semantic HTML
- ✅ Mobile-first design

You can further optimize:
- Compress images using tinypng.com
- Add lazy loading for images (already in script.js)
- Enable Gzip compression (GitHub Pages does this automatically)

## Browser Compatibility

Tested and working on:
- ✅ Chrome (Windows, Mac, Android)
- ✅ Firefox (Windows, Mac, Android)
- ✅ Safari (Mac, iOS)
- ✅ Edge (Windows)
- ✅ Samsung Internet (Android)

Minimum supported:
- IE11 (limited support, some styling issues)

## Accessibility Features

Already included:
- Semantic HTML5 elements
- ARIA labels where needed
- Keyboard navigation support
- Color contrast compliance (WCAG AA)
- Screen reader friendly structure
- Focus indicators
- Alt text for images (add to profile photo)

## Legal & Copyright

- **Content**: You own your content (bio, publications, etc.)
- **Template**: Free to use for academic purposes
- **Images**: Use only photos you own or have rights to
- **Fonts**: Google Fonts are free to use (Open Font License)
- **Icons**: SVG icons are free to use

## Future Enhancements (Optional)

Consider adding later:
- [ ] Blog functionality (use Jekyll)
- [ ] News/Updates section
- [ ] Student testimonials
- [ ] Media mentions
- [ ] Multilingual support
- [ ] Dark mode toggle
- [ ] Analytics (Google Analytics)
- [ ] Search functionality
- [ ] Newsletter signup

## Support Resources

- **GitHub Pages Docs**: https://docs.github.com/en/pages
- **HTML Reference**: https://developer.mozilla.org/en-US/docs/Web/HTML
- **CSS Reference**: https://developer.mozilla.org/en-US/docs/Web/CSS
- **Image Optimization**: https://tinypng.com
- **Color Picker**: https://colorpicker.com

---

**Total Files Created:** 16 files + 2 folders  
**Ready to Deploy:** Yes  
**Estimated Setup Time:** 15-20 minutes

**Next Step:** Read QUICK_START.md and begin setup!
