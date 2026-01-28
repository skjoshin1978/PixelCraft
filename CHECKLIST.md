# ✅ Website Customization Checklist

Use this checklist to personalize your PixelCraft Studio website with your own business information.

---

## 📞 **Contact Information**

### **Phone Numbers**
- [ ] Update phone number in navigation/header
- [ ] Update phone number in footer (all pages)
- [ ] Update "Call Us" buttons and links
- [ ] Update WhatsApp button link
- [ ] Update contact page phone display

**Find & Replace:** `+91 98765 43210` → `YOUR-PHONE-NUMBER`

### **Email Addresses**
- [ ] Update email in footer (all pages)
- [ ] Update "Email Us" buttons and links  
- [ ] Update contact page email display
- [ ] Update form submission email
- [ ] Update Privacy Policy contact email
- [ ] Update Terms & Conditions contact email

**Find & Replace:** `info@pixelcraftstudio.com` → `YOUR-EMAIL@DOMAIN.COM`

### **Business Address**
- [ ] Update footer address (all pages)
- [ ] Update contact page location
- [ ] Update About Us page location
- [ ] Update Google Maps embed
- [ ] Update Privacy/Terms contact section

**Find & Replace:** 
- `Andheri West, Mumbai, Maharashtra` → `YOUR-ADDRESS`
- `Mumbai, India` → `YOUR-CITY-COUNTRY`

---

## 🏢 **Business Information**

### **Company Name**
- [ ] Update logo text in navigation
- [ ] Update page titles (all pages)
- [ ] Update footer company name
- [ ] Update About Us company story
- [ ] Update meta descriptions

**Find & Replace:** `PixelCraft Studio` → `YOUR-COMPANY-NAME`

### **Tagline/Slogan**
- [ ] Update hero section tagline
- [ ] Update footer tagline
- [ ] Update About Us mission

**Current:** "We Build Websites That Build Trust"
**Replace with:** `YOUR-TAGLINE`

---

## 🎨 **Visual Customization**

### **Colors**
Open `styles.css` and update:

- [ ] Primary gradient colors (line ~13)
- [ ] Primary color (line ~14)
- [ ] Accent colors (line ~18)
- [ ] Background colors (line ~21-24)

```css
:root {
  --primary-gradient: linear-gradient(135deg, #YOUR-COLOR-1 0%, #YOUR-COLOR-2 100%);
  --primary-color: #YOUR-MAIN-COLOR;
  --accent-gradient: linear-gradient(135deg, #YOUR-ACCENT-1 0%, #YOUR-ACCENT-2 100%);
}
```

### **Logo**
- [ ] Replace emoji logo (🎨) with your logo image
- [ ] Update favicon in all HTML files
- [ ] Ensure logo is responsive

**Location:** Search for `<span>🎨</span>` in HTML files

### **Fonts** (Optional)
- [ ] Change heading font (currently Playfair Display)
- [ ] Change body font (currently Inter)
- [ ] Update font import in `styles.css`

---

## 📝 **Content Updates**

### **Home Page (`index.html`)**
- [ ] Update hero headline
- [ ] Update hero description
- [ ] Update services descriptions
- [ ] Update statistics numbers
- [ ] Update testimonials (names, companies, reviews)
- [ ] Update "Why Choose Us" content

### **About Page (`about.html`)**
- [ ] Update company story
- [ ] Update mission statement
- [ ] Update vision statement
- [ ] Update core values
- [ ] Update team members (names, roles, descriptions)
- [ ] Update process steps

### **Services Page (`services.html`)**
- [ ] Update service descriptions
- [ ] Update pricing (if applicable)
- [ ] Update what's included lists
- [ ] Update package details

### **Portfolio Page (`portfolio.html`)**
- [ ] Replace project images (Unsplash placeholders)
- [ ] Update project names
- [ ] Update project descriptions
- [ ] Update client names
- [ ] Update case study content

### **Contact Page (`contact.html`)**
- [ ] Update business hours
- [ ] Update FAQ content
- [ ] Update contact form fields (if needed)

---

## 🔗 **Links & URLs**

### **Social Media**
Update in footer and contact page:

- [ ] Facebook URL
- [ ] Twitter URL  
- [ ] Instagram URL
- [ ] LinkedIn URL
- [ ] YouTube URL (if applicable)

**Find & Replace:**
- `https://facebook.com` → `YOUR-FACEBOOK-URL`
- `https://twitter.com` → `YOUR-TWITTER-URL`
- `https://instagram.com` → `YOUR-INSTAGRAM-URL`
- `https://linkedin.com` → `YOUR-LINKEDIN-URL`

### **WhatsApp**
- [ ] Update WhatsApp number
- [ ] Update WhatsApp link

**Find & Replace:** `https://wa.me/919876543210` → `https://wa.me/YOUR-NUMBER`

---

## 🗺️ **Google Maps Integration**

In `contact.html`:

- [ ] Get your Google Maps embed code
- [ ] Replace iframe src with your location
- [ ] Test map loads correctly

**Steps:**
1. Go to Google Maps
2. Search your business location
3. Click "Share" → "Embed a map"
4. Copy iframe code
5. Replace in `contact.html` (around line 183)

---

## 📧 **Contact Form Setup**

Choose and implement ONE option:

### **Option A: FormSpree**
- [ ] Sign up at formspree.io
- [ ] Get your form endpoint
- [ ] Update form action attribute
- [ ] Test form submission

```html
<form action="https://formspree.io/f/YOUR-FORM-ID" method="POST">
```

### **Option B: EmailJS**
- [ ] Sign up at emailjs.com
- [ ] Create email template
- [ ] Get service ID and template ID
- [ ] Add EmailJS SDK to HTML
- [ ] Update form handler in `script.js`
- [ ] Test form submission

### **Option C: Custom Backend**
- [ ] Create backend endpoint
- [ ] Update form action URL
- [ ] Implement server-side validation
- [ ] Set up email sending
- [ ] Test form submission

---

## 🔍 **SEO Optimization**

### **Meta Tags (All Pages)**
- [ ] Update page titles (51-60 chars)
- [ ] Update meta descriptions (150-160 chars)
- [ ] Add keywords relevant to your business
- [ ] Update Open Graph tags
- [ ] Add Twitter Card meta tags

### **Content**
- [ ] Ensure proper H1 hierarchy (one per page)
- [ ] Add alt text to all images
- [ ] Use descriptive link text
- [ ] Add structured data markup (optional)

---

## 📸 **Images**

### **Portfolio Images**
- [ ] Replace Unsplash placeholders with your projects
- [ ] Optimize images (compress with TinyPNG)
- [ ] Ensure images are web-optimized (< 200KB each)
- [ ] Use descriptive filenames
- [ ] Add proper alt text

### **Team Photos** (About Page)
- [ ] Add actual team photos
- [ ] Or keep initials in circles
- [ ] Ensure consistent sizing

---

## 🎯 **Legal Pages**

### **Privacy Policy (`privacy.html`)**
- [ ] Update company name
- [ ] Update contact information
- [ ] Review data collection practices
- [ ] Update based on your actual policies
- [ ] Add jurisdiction if needed
- [ ] Update last modified date

### **Terms & Conditions (`terms.html`)**  
- [ ] Update company name
- [ ] Update contact information
- [ ] Review service terms
- [ ] Update pricing/payment terms
- [ ] Add specific policies for your business
- [ ] Update last modified date
- [ ] Review with legal advisor (recommended)

---

## 🔐 **Security & Performance**

### **Before Launch**
- [ ] Remove any test/placeholder content
- [ ] Test all forms work correctly
- [ ] Verify all links are working
- [ ] Check responsive design on mobile
- [ ] Test in multiple browsers
- [ ] Run Google PageSpeed Insights
- [ ] Set up SSL certificate (HTTPS)
- [ ] Configure 404 error page (optional)

### **Analytics & Tracking**
- [ ] Add Google Analytics code
- [ ] Add Facebook Pixel (if needed)
- [ ] Set up Google Search Console
- [ ] Create sitemap.xml (optional)
- [ ] Create robots.txt (optional)

---

## 🚀 **Deployment**

### **Pre-Launch Checklist**
- [ ] All content reviewed and approved
- [ ] All links tested
- [ ] Contact form tested and working
- [ ] Mobile responsive verified
- [ ] Browser compatibility tested
- [ ] SEO meta tags complete
- [ ] Images optimized
- [ ] Analytics installed
- [ ] SSL certificate ready

### **Launch**
- [ ] Upload files to hosting
- [ ] Configure domain DNS
- [ ] Test live website
- [ ] Submit to Google Search Console
- [ ] Create Google My Business listing
- [ ] Share on social media
- [ ] Monitor for any issues

---

## 📊 **Post-Launch**

### **Week 1**
- [ ] Monitor analytics
- [ ] Check for broken links
- [ ] Test contact form submissions
- [ ] Review mobile performance
- [ ] Collect initial feedback
- [ ] Fix any bugs

### **Ongoing**
- [ ] Regular backups
- [ ] Update content regularly
- [ ] Monitor site speed
- [ ] Review analytics monthly
- [ ] Update portfolio with new projects
- [ ] Keep software/plugins updated
- [ ] Monitor and respond to inquiries

---

## 🎨 **Optional Enhancements**

Consider adding later:
- [ ] Blog section
- [ ] Newsletter signup
- [ ] Live chat widget
- [ ] Customer login area
- [ ] Testimonials slider
- [ ] Video backgrounds
- [ ] Animation improvements
- [ ] Additional pages
- [ ] Multi-language support
- [ ] Dark mode toggle

---

## 🆘 **Resources**

### **Image Resources**
- Unsplash: unsplash.com (free photos)
- Pexels: pexels.com (free photos)
- TinyPNG: tinypng.com (image compression)

### **Icons**
- Font Awesome: fontawesome.com (currently used)
- Heroicons: heroicons.com
- Feather Icons: feathericons.com

### **Colors**
- Coolors: coolors.co (color palette generator)
- Adobe Color: color.adobe.com

### **Fonts**
- Google Fonts: fonts.google.com
- Font Pair: fontpair.co (font combinations)

### **Testing**
- Google PageSpeed: pagespeed.web.dev
- Mobile Test: search.google.com/test/mobile-friendly
- W3C Validator: validator.w3.org

### **Form Services**
- FormSpree: formspree.io (easiest)
- EmailJS: emailjs.com
- Netlify Forms: netlify.com/products/forms

---

## ✅ **Quick Wins**

**Most Important Items (Do These First):**

1. ✅ Replace all phone numbers
2. ✅ Replace all email addresses
3. ✅ Update company name
4. ✅ Update business address
5. ✅ Configure contact form
6. ✅ Update Google Maps
7. ✅ Update social media links
8. ✅ Replace WhatsApp number
9. ✅ Update portfolio images
10. ✅ Test on mobile device

---

## 📝 **Notes**

- Save a backup before making major changes
- Test after each significant update
- Use "Find & Replace" in code editor for efficiency
- Mobile-test every change
- Keep track of what you've customized

---

## 🎉 **Completion**

Once you've checked off all items:

✅ **Your website is fully customized!**
✅ **Ready for launch!**
✅ **Time to go live!**

---

**Need Help?**
📧 Email: info@pixelcraftstudio.com
📱 Phone: +91 98765 43210
💬 WhatsApp: wa.me/919876543210

**Good luck with your website launch! 🚀**

---

*Checklist created for PixelCraft Studio Website Template*
*Last Updated: January 28, 2026*
