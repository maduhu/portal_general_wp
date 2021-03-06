Cherry Framework 4
==================================

Cherry Framework 4 is a theme configuration framework for Wordpress CMS. Framework itself contain a starter parent theme, theme configuration options, post formats templates etc. Cherry Framework parent theme is based on underscores.me started theme for WordPress with enhanced functionality and extended possibilities.

From the box Cherry Framework 4 offers:
* __Theme configuration options__ (layout options, blog settings, styling options, navigation options, typography settings etc.).
* __Post format templates__. Each Wordpress post type has it's own template with unique markup.
* __Post layouts__. You can confugure page layout for each post individually.
* __Static editor__. With easy to use drag-n-drop interface you can configure blocks in static areas (header, footer, showcase etc.)

You can learn more about Cherry Framework 4 features from the [official documentation](http://www.cherryframework.com/documentation/cf4/index_en.html)

##Change log##

#### v4.0.3 ####

* UPD: Including assets for a `Interface Builder` and `Static Page`
* UPD: UI-elements optimization

#### v4.0.2 ####

* NEW: Feature - formatting the `chat` post format
* ADD: Support microformats (xfn)
* ADD: Options visibility
* ADD: Hidden value for `ui-repeater` element
* UPD: Rename `blank.pot` to `cherry.pot`
* UPD: Custom menu registration
* UPD: Optimazed slow queries in DB
* UPD: .po files
* UPD: Compressed a third-party css
* FIX: Sanitize for a custom static classes
* FIX: php-notice on 404-page
* FIX: Prevent PHP errors caused by CSS compiler
* DEL: Unnecessary using var `global $cherry_registered_statics`

#### v4.0.1 ####

* ADD: statics visibility feature
* ADD: `rtl.css`
* ADD: WPML-plugin support
* ADD: enable/disable option for a single post navigation
* ADD: a control classes for page `<article>`
* ADD: `large` CSS-class to the post-format image
* FIX: php-notice
* FIX: enqueue `magnific-popup` script
* FIX: default theme options creating
* FIX: `footer-sidebars` static
* UPD: translated text
* UPD: languages files
* UPD: change `require_once` to `include` while including dynamic CSS files in CSS compiler
* UPD: button colors (in options page)
* UPD: `Post content` option
* UPD: `cherry_typography_size` function
* UPD: `magnific-popup.css`