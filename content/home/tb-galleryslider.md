---
weight: 1
title: Slider-Gallery-Carousel
---
This executes the gallery-slider shortcode command in /content/home/tb-galleryslider.md

### This plays images in /static/media;  one edit, and it plays /assets/media
The source directory is named in the shortcode, relative to /static.  Update by changing /layouts/shortcodes/tb-slider.html, line 89 from "static" to "assets"


{{< gallery-slider dir="/media/" width="400px" height="400px" auto-slide="2000" >}}

Created by tbiering/hugo-slider-shortcode <a href="https://github.com/tbiering/hugo-slider-shortcode"> Thomas Biering </a>

