# Website Testing Checklist

##  Manual Testing Guide

### Navigation Testing
- [ ] Click each navigation link (Home, About Me, Resume, Projects, Contact)
- [ ] Verify active page highlighting in navigation
- [ ] Test navigation on mobile devices (use browser dev tools)
- [ ] Ensure logo links back to homepage

### Page-by-Page Testing

#### Homepage (index.html)
- [ ] Profile image displays correctly
- [ ] Hero text is readable and properly formatted
- [ ] "Resume" button links to Resume.pdf (add PDF file first)
- [ ] "Open to Opportunities" button links to contact page
- [ ] Responsive design works on different screen sizes

#### About Page (about.html)
- [ ] Biography text displays properly
- [ ] "Outside the Classroom" section is visible
- [ ] About images display (add about1.jpg and about2.jpg first)
- [ ] Image hover effects work
- [ ] Content is readable on mobile

#### Resume Page (resume.html)
- [ ] All sections (Education, Experience, Projects, Skills) display
- [ ] "Download PDF Resume" button works (add Resume.pdf first)
- [ ] Skills grid layout is responsive
- [ ] Dates and formatting are consistent
- [ ] Content is organized and scannable

#### Projects Page (projects.html)
- [ ] All 4 project cards display properly
- [ ] Project images load (add project images first)
- [ ] Tech stack tags are visible
- [ ] GitHub links work (update with real URLs)
- [ ] Card hover effects function
- [ ] Grid layout is responsive

#### Contact Page (contact.html)
- [ ] Contact links work (email, LinkedIn, GitHub)
- [ ] Contact form displays all fields
- [ ] Form validation works:
  - [ ] Required fields show errors when empty
  - [ ] Email validation works
  - [ ] Password minimum length (8 chars) enforced
  - [ ] Password confirmation matching works
- [ ] Form submission redirects to thank you page

#### Thank You Page (thankyou.html)
- [ ] Page displays after form submission
- [ ] Links back to other pages work
- [ ] Styling is consistent

### Responsive Design Testing
- [ ] Test on desktop (1200px+)
- [ ] Test on tablet (768px - 1199px)
- [ ] Test on mobile (< 768px)
- [ ] Navigation collapses appropriately on mobile
- [ ] Images scale properly
- [ ] Text remains readable at all sizes

### Accessibility Testing
- [ ] Tab through all interactive elements
- [ ] All images have alt text
- [ ] Form labels are properly associated
- [ ] Color contrast is sufficient
- [ ] Headings follow logical hierarchy

### Performance Testing
- [ ] Pages load quickly
- [ ] Images are optimized for web
- [ ] No console errors in browser dev tools
- [ ] CSS and HTML validate (see validation section below)

##  Technical Testing Tools

### Browser Developer Tools
1. **Open Dev Tools**: Right-click → Inspect Element (or F12)
2. **Console Tab**: Check for JavaScript errors
3. **Network Tab**: Monitor loading times and failed requests
4. **Responsive Design Mode**: Test different screen sizes

### Cross-Browser Testing
Test in multiple browsers:
- [ ] Chrome
- [ ] Firefox
- [ ] Safari
- [ ] Edge

### Validation Testing
- [ ] HTML Validation: https://validator.w3.org/
- [ ] CSS Validation: https://jigsaw.w3.org/css-validator/

##  Common Issues to Check

### Missing Assets
- [ ] Profile image (images/profile.jpg)
- [ ] About page images (images/about1.jpg, about2.jpg)
- [ ] Project images (images/*.jpg)
- [ ] Resume PDF (Resume.pdf)

### Form Issues
- [ ] Password confirmation matching
- [ ] Email format validation
- [ ] Required field validation
- [ ] Form submission redirect

### Layout Issues
- [ ] Text overflow on small screens
- [ ] Image sizing and aspect ratios
- [ ] Button alignment
- [ ] Grid layout on mobile

### Link Issues
- [ ] Internal navigation links
- [ ] External links (LinkedIn, GitHub, Email)
- [ ] PDF download link
- [ ] Target="_blank" for external links

## 📱 Mobile Testing Commands

### Using Browser Dev Tools:
1. Open browser dev tools (F12)
2. Click device icon (responsive design mode)
3. Test common device sizes:
   - iPhone SE (375px)
   - iPhone 12 Pro (390px)
   - iPad (768px)
   - iPad Pro (1024px)

### Physical Device Testing:
- Test on actual mobile devices if available
- Check touch interactions
- Verify zoom behavior
- Test form input on mobile keyboards

## 🔧 Quick Fixes for Common Issues

### If images don't load:
- Check file paths in HTML
- Ensure images are in correct directory
- Verify image file names match HTML references

### If forms don't work:
- Check form action URL
- Verify input names and IDs
- Test JavaScript validation

### If styles look broken:
- Check CSS file linking
- Verify CSS syntax
- Clear browser cache

##  Testing Completion

**Test Date**: ___________
**Tested By**: ___________
**Browser(s)**: ___________
**Device(s)**: ___________

**Issues Found**: 
_________________
_________________
_________________

**Status**: [ ] Passed [ ] Needs Fixes [ ] Ready for Deployment
