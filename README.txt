SRI VENKATESHWARA HANDLOOMS — IMAGE SETUP GUIDE
=================================================

HOW THIS WORKS
--------------
The website (index.html) is already coded to look for images at exact
file paths inside the "assets" folder next to it. You do NOT need to
touch any code. Just save your images with the exact filenames below,
inside the matching folder, and the site will pick them up automatically
when you open index.html.

If a file is missing, that spot will show a soft placeholder background
instead of a broken image icon — so it's safe to add images gradually.


FOLDER STRUCTURE
-----------------
site-package/
├── index.html                          <- the website, don't rename
└── assets/
    ├── logo.png                        <- your logo (square works best)
    ├── hero.jpg                        <- big homepage banner image
    ├── promo.jpg                       <- "Flat ₹1,500 Off" banner image
    ├── category-hero.jpg               <- top banner on category pages
    ├── categories/
    │   ├── kanjivaram.jpg
    │   ├── banarasi.jpg
    │   ├── mysore.jpg
    │   ├── cotton.jpg
    │   └── bridal.jpg
    └── products/
        ├── 1-1.jpg   1-2.jpg   1-3.jpg      <- Product #1, 3 photos
        ├── 2-1.jpg   2-2.jpg   2-3.jpg      <- Product #2, 3 photos
        ├── 3-1.jpg   3-2.jpg   3-3.jpg      <- Product #3, 3 photos
        ... continues through ...
        └── 16-1.jpg  16-2.jpg  16-3.jpg     <- Product #16, 3 photos


WHAT EACH FILE IS FOR
----------------------

logo.png
  Shown in the header (top-left) and footer. Square image works best
  (e.g. 200x200px). PNG with transparent background is ideal, but JPG
  works too.

hero.jpg
  The large full-width image at the very top of the homepage, behind
  the "Woven by hand, worn for generations" headline. Recommended
  size: 1920x1080px or similar wide landscape shot.

promo.jpg
  The banner image behind the "Premium Silk Collection — Flat ₹1,500
  Off" section, midway down the homepage. Recommended: 1600x900px.

category-hero.jpg
  The banner shown at the top when someone clicks into a category page
  (e.g. clicking "Kanjivaram Silk"). Recommended: 1600x700px.

assets/categories/*.jpg
  The 5 photo tiles in the "Find your kind of silk" section on the
  homepage — one per weave type:
    kanjivaram.jpg  -> Kanjivaram Silk tile
    banarasi.jpg    -> Banarasi Silk tile
    mysore.jpg      -> Mysore Silk tile
    cotton.jpg      -> Handloom Cotton tile
    bridal.jpg      -> Bridal Edit tile
  Recommended: roughly square/portrait, 800x880px.

assets/products/N-1.jpg, N-2.jpg, N-3.jpg
  Each product card shows 3 images in a small swipeable gallery.
  N is the product number (1 through 16). So:
    1-1.jpg, 1-2.jpg, 1-3.jpg  = the 3 photos for Product 1
    2-1.jpg, 2-2.jpg, 2-3.jpg  = the 3 photos for Product 2
    ...and so on through 16.
  Recommended: square images, 700x700px or larger, consistent
  lighting/background across all three for a clean look.

  Here's which product each number refers to, so you know which
  saree's photos go where:

   1  Maroon & Gold Zari Kanjivaram Silk Saree
   2  Banarasi Silk Saree with Gold Zari Border
   3  Handwoven Ikat Cotton Saree, Everyday Wear
   4  Mysore Crepe Silk Saree, Temple Border
   5  Bridal Red Kanjivaram with Peacock Motif Pallu
   6  Chettinad Cotton Saree, Handloom Checks
   7  Banarasi Katan Silk Saree, Meenakari Weave
   8  Pure Mysore Silk Saree, Zari Checked Body
   9  Emerald Green Kanjivaram Silk, Contrast Pallu
  10  Handloom Linen-Cotton Saree, Daily Office Wear
  11  Banarasi Organza Silk Saree, Floral Jaal
  12  Bridal Gold Kanjivaram Silk, Temple Border Pallu
  13  Royal Blue Kanjivaram with Kanchi Border
  14  Banarasi Tissue Silk Saree, Gold Booti Work
  15  Mysore Silk Saree with Contrast Zari Pallu
  16  Ivory & Gold Kanjivaram, Bridal Reception Edit

  (You can rename/reassign which saree is which later by editing the
  "title" text in the PRODUCTS list inside index.html — but the image
  file numbering will still follow the product's position, 1 to 16.)


ONLY HAVE SOME IMAGES RIGHT NOW?
----------------------------------
That's fine. Add whatever you have — the rest will show a neutral
placeholder until you add them. No missing file will break the page
or show a broken-image icon.

If a product only has 1 or 2 real photos instead of 3, you can just
save the same photo as both N-2.jpg and N-3.jpg (or any photo) as a
placeholder until you have more.


FILE TYPES
-----------
.jpg or .png both work fine everywhere above — just make sure the
filename (before the dot) matches exactly what's listed, including
lowercase letters and no spaces.
