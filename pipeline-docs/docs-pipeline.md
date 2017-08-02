Pipeline Theme
================

The Pipeline documentation has moved to a new format - the new and improved docs are here:

<a class="button" href="http://help.groupthought.com/">Go to documentation</a>


Releases
===========

#### Version 1.0.1
- Fixed footer logo alignment
- Fixed jagged scrolling on homepage

#### Version 1.0.2
- Fixed broken links caused by homepage custom section
- Better vertical spacing for non-white background colors

#### Version 1.1
- product home page settings mention four product limit that no longer exists
- hero was locked in full screen - fixed
- Responsive Imges in RTE
- remove columns from homepage
- Support article.image
- Support new Shopify standard theme settings
- Support Apple Wallet gift cards
- Upgraded theme settings for clarity
- Homepage 2 recent blog posts
- Homepage up to six logos of prominent customers/news media/partners/vendors
- Homepage titles for each section
- Homepage section background colors
- Homepage cleaner design for page - split into columns
- Javascript performance improvements
- Constrain wide logos on mobile devices
- Aligned: collection text, product social icons, pagination, footer social links

#### Version 1.2
- Theme settings updated to match Shopify best practices
- Headings use separate font from body font

#### Version 1.3
This update removes Instagram integration due to API policy changes, and releases small bug fixes.

- Remove instagram integration
- Load js if fastclick fails
- Remove english word - more
- Fix iOS safari scroll on initial page load issue by updating typekit
- Add default centering on list template
- Fix link element closing order for theme credit list item

#### Version 1.4
- Replace Instagram integration with new token settings

#### Version 1.5
- Add banner controls for image width and height
- Add parallax option to banner and video section
- Square crop insatgram photos
- Add Instagram controls for photo count
- Add Blog controls for number of posts
- Move video into its own section with identical functionality to banner and youtube support
- New arrow style and animation on Banner
- Add section for optional second page of page content on home page
- Add option to not open the cart modal when a uses adds an item to the cart
- Add product thumbnail photos
- Remove 1px line from below last item on mobile dropdown
- Update icons to include amazon payments
- Allow collection sidebar tags to be removed one by one instead of all at once
- Remove legacy checkout.css file
- Fix issue where featured product would not show on home page if theme settings did not have a featured page
- Fix meganav subheading links on iPad

#### Version 1.6
- Update Instagram, Google and payment icons
- More reliable variant-image matching for edge cases
- Simplify cart link setttings
- Minor SEO tweaks for Panda and Rankbrain
- Alow standard nav on collections template
- Simplify collections list page and footer colors

#### Version 1.7
- Apple Pay support
- Prevent related videos from showing on YouTube videos loaded from Homepage video section

#### Version 2.0
- Add support for the new theme editor
- Convert home page to modular sections
- Change variant code to new system without option_select.js

#### Version 2.1
- Fix bug in new variant system affecting stores with multiple variant dropdowns where the first variant was added to the cart instead of the selected variant

#### Version 2.2 (December 15 2016)
- Additional variant fixes
- Include a home page slideshow
- Include zoom on the product page
- Change form selector to basic class selector — allowing language params to be passed into checkout
- Update icons to contain left right slideshow arrows (so slideshow arrows can inherit color from the text)
- Center products in collections containing less that one full row of products
- Add title to the rich text block — allowing it to visually match the other sections


#### Version V2.3  (February 24 2017)
- Add a collection grid section for home page
- Add view all button to the featured collection section on home page
- Improve schema tags on product and article
- Remove outdated image size recommendations
- Indicate sold out items in single variant dropdown
- Unify aesthetic and animations of featured news section with the new collection grid section
- Fix z-index on article featured images for mobile
- Fire variant JS on pageload for more consistent sold-out edge case handling
- Fix color name typo in dropdown icon SVG
- Remove return false in Pipeline.smoothScroll JS to allow additional events on anchor tag clicks
- Show digital orders in account and hide quantity on membership products
- Add wrapper to collection template text without image for better mobile text display

#### Version V2.4 (April 17 2017)
- Escape all text settings
- Add block.shopify attributes to blocks missing them
- Add product video functionality via image alt text
- Allow product description split with `[split]`
- Add side-by-side section (image and text)
- Add logo section
- Add columns section
- Add filter toggle to collection mobile view
- Better alignment on first dropdown in the main menu
- Top bar mobile improvements

#### Version V2.4.1 (July 11 2017)
- Add Shopify Pay logo
- Fix name conflict on matchHeight function
- Add vertical padding between columns on mobile version of columns section
- Decrease banner button size on mobile
- Hide slides while slideshow is loading
- Remove outline on hero scroll arrow

#### Version V3.0 (August 2 2017)
- Corknine Themes is now Groupthought
- Change numeric dropdowns to sliders
- Product section now has blocks for configuring tabs
- Default home page has a better demonstration of the available sections
- Mobile chrome experience is updated to prevent jagged scroll while chrome hides the URL bar
- Product page now has the option to add a sizing chart popup
- Collection template now has the option to add sale, new and sold out stickers to the grid of images
- The general social settings now has an option to add a default sharing image for the homepage
- Update the product variant dropdown to use the new has_only_defaults variable instead of the "default" string check
- Always show the image above the text on mobile version of "Image and text" section, regardless of their order in the desktop view
- Allow the product image zoom to show an image that takes the full width of the page
