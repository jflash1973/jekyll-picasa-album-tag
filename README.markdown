## Usage:
Simply open any Picasa album and you will find an RSS link on the right panel.
Copy that link and paste it into your page like this:

`` {% picasa_album <link_to_album_rss_feed %} ``

## Configuration
Configuration is done via the ``_config.yml`` file.  

### Example:
``
picasa_album:
  thumbnail_size: 0
  gallery_tag: div
  gallery_class: gallery
  a_class: fancybox
``

### Known options:
 - thumbnail_size, default=1, values=0-2
 - gallery_tag, default=div
 - gallery_class, default=
 - title_tag, default=h2
 - a_rel, default=/[0-9]+/.match(rss_url)
 - a_class, default=
 - a_target, default=
 - img_rel, default=
 - img_class, default=
