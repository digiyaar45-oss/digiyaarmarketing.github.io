# Digiyaar - Digital Marketing Agency Website

## GitHub Pages par Deploy karne ka tareeqa:

### Method 1: Direct Upload (Asaan Tareeqa)

1. **GitHub par jao** aur apne repository mein jao:
   - https://github.com/digiyaar45-oss/digiyaarmarketing.github.io

2. **Purani files delete karo** (agar hain toh)

3. **"Add file" > "Upload files"** par click karo

4. **Is folder ki SAARI files** ko drag and drop karo ya select karo:
   - index.html
   - about.html
   - blog.html
   - careers.html
   - contentstrategy.html
   - freeaudittools.html
   - marketingautomation.html
   - newsletter.html
   - ourteam.html
   - paidmedia.html
   - portfolio.html
   - services.html
   - README.md

5. **"Commit changes"** par click karo

6. **Repository Settings** mein jao:
   - "Settings" tab par click karo
   - Left sidebar mein "Pages" par click karo
   - Source: "main" branch select karo
   - Save karo

7. **Thode der mein website live ho jayegi:**
   - https://digiyaar45-oss.github.io/digiyaarmarketing.github.io/

---

### Method 2: Git Commands (Agar Git use karte ho)

```bash
# Repository clone karo
git clone https://github.com/digiyaar45-oss/digiyaarmarketing.github.io.git
cd digiyaarmarketing.github.io

# Purani files delete karo (agar hain)
rm -rf *

# Nayi files copy karo (is folder se)
cp /path/to/digiyaar-website/* .

# Git mein add karo
git add .
git commit -m "Updated complete website with all pages"
git push origin main
```

---

## Website Structure:

```
digiyaarmarketing.github.io/
├── index.html              (Home Page)
├── about.html              (About Us)
├── services.html           (Services)
├── portfolio.html          (Portfolio)
├── blog.html               (Blog)
├── careers.html            (Careers)
├── case-studies.html       (Case Studies) ✨ NEW
├── contentstrategy.html    (Content Strategy Service)
├── seo-ai-search.html      (SEO & AI Search / AEO Service)
├── freeaudittools.html     (Free Audit Tools)
├── marketingautomation.html (Marketing Automation Service)
├── newsletter.html         (Newsletter)
├── ourteam.html            (Our Team)
├── paidmedia.html          (Paid Media Service)
├── README.md               (Ye file)
└── CHANGELOG.md            (Updates log)
```

---

## Important Notes:

✅ **Saari files ek hi repository mein hain**
✅ **Links sab relative hain (index.html, about.html, etc.)**
✅ **Blogspot links remove kar diye gaye hain**
✅ **CSS aur JavaScript sab HTML mein inline hain**
✅ **Newsletter page header mein properly linked hai**
✅ **SEO & AI Search (AEO) page banaya gaya hai**
✅ **"Back to Blogs" ko "Back to Home Page" change kar diya**
✅ **Case Studies page banaya gaya hai**
✅ **LIGHT THEME - White background, Red typography** ✨ NEW

---

## Agar koi problem ho:

1. Check karo ke **index.html** file repository mein hai (ye main page hai)
2. **GitHub Pages** Settings mein dekho ke "main" branch selected hai
3. 2-5 minute wait karo, phir website check karo
4. Browser cache clear karo (Ctrl+Shift+Delete)

---

**Website URL:** https://digiyaar45-oss.github.io/digiyaarmarketing.github.io/

**Contact:** Digiyaar Marketing Team
