## Discourse Age of Empires Theme

More info at: http://www.ageofempires.com/discourse/theme/about

The following information may be found at [https://meta.discourse.org/t/how-to-develop-custom-themes/60848!](https://meta.discourse.org/t/how-to-develop-custom-themes/60848)

### About File
about.json (required)

The about.json file structure is:

<addr>
{
  "name": "The name of your theme",
  "about_url": "http://somesite.com/about_your_theme",
  "license_url": "http://somesite.com/license",
   "assets": {
       "font": "assets/some_font.woff2"
   },
   "color_schemes": {
       "Scheme Name": {
          "primary": "AAABBB"
        }
    }
}
</addr>

### Common Files
common/common.scss

common/header.html

common/after_header.html

common/footer.html

common/head_tag.html

common/body_tag.html

common/embedded.scss

### Desktop Files
desktop/desktop.scss

desktop/header.html

desktop/after_header.html

desktop/footer.html

desktop/head_tag.html

desktop/body_tag.html

### Mobile Files
mobile/mobile.scss

mobile/header.html

mobile/after_header.html

mobile/footer.html

mobile/head_tag.html

mobile/body_tag.html

### Settings File
settings.yml

Instructions on how to add settings to your theme available at 
(https://meta.discourse.org/t/how-to-add-settings-to-your-discourse-theme/82557)