================================================
  TrendWear Fashion Neral — Website README
================================================

FOLDER STRUCTURE
----------------
shop-website/
 ├── index.html         ← Main website file
 ├── css/
 │    └── style.css     ← All styles
 ├── js/
 │    └── script.js     ← Interactivity (filter, scroll, menu)
 ├── images/            ← (Optional) Add local product images here
 └── README.txt         ← This file


HOW TO RUN
----------
1. Open the "shop-website" folder.
2. Double-click "index.html" to open it in your browser.
   ✅ No server needed — it works offline too!
   (Note: Google Maps embed requires internet.)


HOW TO CHANGE WHATSAPP NUMBER
-------------------------------
1. Open index.html in any text editor (Notepad, VS Code, etc.)
2. Press Ctrl+H (Find & Replace)
3. Find:    919987654321
   Replace: 91XXXXXXXXXX   (your 10-digit number with country code 91)
4. Save the file.
   That's it! All buttons update at once.


HOW TO CHANGE WHATSAPP MESSAGE
--------------------------------
1. In index.html, find:
   text=Hi%2C%20I%20want%20to%20order%20products%20from%20TrendWear%20Fashion.
2. Replace the text after "text=" with your custom message.
   Use %20 for spaces, %2C for commas.
   Example: "Hi, I want to order" → Hi%2C%20I%20want%20to%20order


HOW TO CHANGE / ADD PRODUCTS
------------------------------
1. Open index.html and find the section:
   <!-- ============ PRODUCTS ============ -->

2. Copy any existing <div class="product-card"> block.

3. Change:
   - Image: Replace the Unsplash URL with your image URL or local path
     e.g., images/my-shirt.jpg
   - Name: Change the text inside <h4>Product Name</h4>
   - Price: Change ₹499 to your actual price
   - Original Price: Change ₹699 to old/strikethrough price
   - Category: Change data-cat="men" to men / women / accessories
   - Badge text: Change "Men" / "Women" / "Accessories" accordingly
   - WhatsApp link: Update the product name in the URL

4. Save and refresh.


HOW TO CHANGE PRODUCT PRICES
------------------------------
Find the product card and update:
  <span class="price">₹499</span>          ← Selling price
  <span class="price-orig">₹699</span>     ← Original / strikethrough price


HOW TO USE LOCAL IMAGES
------------------------
1. Put your image files into the "images/" folder
2. In index.html, replace Unsplash URLs like:
   src="https://images.unsplash.com/..."
   with:
   src="images/your-image.jpg"


HOW TO CHANGE STORE NAME / ADDRESS / HOURS
--------------------------------------------
Search in index.html for:
  - "TrendWear Fashion"       → Your store name
  - "Main Market Road, Neral" → Your address
  - "10:00 AM – 9:30 PM"     → Your timings
  - "+91 99876 54321"         → Your phone number


HOW TO CHANGE THE GOOGLE MAP
------------------------------
1. Go to maps.google.com
2. Search your store location
3. Click Share → Embed a Map → Copy HTML
4. In index.html, find <iframe ... title="TrendWear...">
5. Replace the entire src="..." URL with the new one from Google.


HOW TO ZIP THIS FOLDER
-----------------------
Windows:
  1. Right-click the "shop-website" folder
  2. Select "Send to" → "Compressed (zipped) folder"
  3. You'll get "shop-website.zip"

Mac:
  1. Right-click the "shop-website" folder
  2. Select "Compress 'shop-website'"
  3. You'll get "shop-website.zip"

Linux:
  Run in terminal:
  zip -r shop-website.zip shop-website/


HOW TO DEPLOY ONLINE (FREE)
-----------------------------
Option 1 — Netlify Drop (Easiest):
  1. Go to https://app.netlify.com/drop
  2. Drag and drop the "shop-website" folder
  3. Your site is live in seconds!

Option 2 — GitHub Pages:
  1. Upload to a GitHub repo
  2. Settings → Pages → Deploy from main branch

Option 3 — Tiiny.host:
  1. Go to https://tiiny.host
  2. Upload the zip file
  3. Get a free live link


CUSTOMIZATION QUICK REFERENCE
-------------------------------
| What             | Where in index.html              |
|------------------|----------------------------------|
| Store name       | .logo-main, footer, title tag    |
| Tagline          | hero-sub, footer brand p         |
| WhatsApp number  | All href="https://wa.me/..."     |
| Products         | #products section                |
| Offers text      | .offers-strip section            |
| About text       | .about-section                   |
| Reviews          | .reviews-section                 |
| Address/Hours    | .contact-section                 |
| Map              | iframe in .contact-section       |
| Accent color     | :root --accent in style.css      |


TECH STACK
-----------
- HTML5
- CSS3 (custom properties, grid, flexbox, animations)
- Vanilla JavaScript (ES6+)
- Google Fonts: Cormorant Garamond + DM Sans
- Images: Unsplash (free, no attribution required)

================================================
  Built for TrendWear Fashion Neral, 2025
================================================
