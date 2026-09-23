# Ishi Cooks — Modern GitHub Pages Website

## Included
- Modern sticky header and mobile navigation
- Search + category filters
- Add-to-cart quantity controls
- Half/Full choices for applicable dishes
- WhatsApp checkout with automatic order summary
- Photo gallery ready for real food photos
- Customer testimonials section
- Google Maps location button
- Floating WhatsApp button
- Responsive mobile design
- Custom 404 error page
- `config.js` makes future menu/price/photo/testimonial edits easy

## Publish
1. Create a public GitHub repository.
2. Upload all files/folders in this package.
3. GitHub: Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
4. Your website will be available at `https://YOUR-USERNAME.github.io/REPOSITORY/`.

## Easy editing
Most changes are in **config.js**:
- Business phone/WhatsApp/Maps link
- Menu and prices
- Gallery filenames
- Testimonials

### Add photos
Put your real photos in `assets/gallery/`, then change the corresponding paths in `config.js`.

### Testimonials
Replace the sample testimonial text with genuine customer reviews before publishing.


## Delivery
Edit `SITE_CONFIG.business.delivery` in `config.js`. The website provides buttons for Porter and Uber Parcel/Uber Connect. These are third-party booking links; customers arrange the delivery themselves.

## Vacation / kitchen closed notice
Set `SITE_CONFIG.business.vacation.enabled` to `true` in `config.js` whenever the kitchen is closed. Edit `title`, `message`, `from`, `to`, and `reopenText`. Set it back to `false` when you reopen.

## Google Maps
The location section contains a real Google Maps iframe centered at the Ishi Cooks coordinates resolved from the supplied Google Maps link, plus the original Google Maps place link.


### Delivery links
Customers can open Porter or Uber Parcel/Uber Connect from the Delivery section and arrange a rider themselves. These third-party links are editable in `config.js`.

### Vacation popup
Turn `SITE.business.vacation.enabled` to `true` in `config.js` whenever the kitchen is closed. Set the dates and message there. Turn it back to `false` when you reopen.

### Google Maps
The Location section includes a real Google Maps iframe centered on the Ishi Cooks coordinates from the supplied Google Maps place link, plus the original place link.
