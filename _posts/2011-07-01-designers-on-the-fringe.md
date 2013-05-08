---

layout: two-column

stamp:
  month: true

images: 
  - alt: Designers on the Fringe
    src: /images/designers-on-the-fringe.png
  - alt: Designers on the Fringe Icon
    src: /images/designers-on-the-fringe-icon.png

gallery:
  one:
    - alt: Designers on the Fringe Silhouette
      src: /images/designers-on-the-fringe-silhouette.jpg
      href: "http://www.reversemymenopause.com/silhouette1.jpg"
      span: 2
    - alt: Designers on the Fringe Photo
      src: /images/designers-on-the-fringe-photo.jpg
      href: "http://2.bp.blogspot.com/-iRVXoTLb9Cw/Tmb8abk7bwI/AAAAAAAABzs/sQ71uwPQYQ0/s1600/116002_1298051032.jpg"
      span: 2
  two:
    - alt: Designers on the Fringe Bow
      src: /images/designers-on-the-fringe-silhouette-bow.png
      href: /images/designers-on-the-fringe-silhouette-bow.png
      span: 2
    - alt: Designers on the Fringe Icon
      src: /images/designers-on-the-fringe-icon.png
      span: 2
  three:
    alt: Designers on the Fringe Mockup
    src: /images/designers-on-the-fringe-mockup.png
    href: /images/designers-on-the-fringe-mockup.png

tags:
  illustrator
  illustration
  icon
  tumblr
  web
  design

---

This was a freelance project that I undertook while in college. I had an ad on [craigslist](http://craigslist.org) offering my web-design services with a link to my portfolio. I was sought out by this client to do a wordpress or tumblr theme, In the beginning of the project chose tumblr. It was requested of my that I enable [disqus](http://disqus.com) comments to the theme as well. The site had a good run but has since been removed, once visible at [askmrsdof.tumblr.com](http://askmrsdof.tumblr.com/) and unretrievable by the [wayback machine](http://web.archive.org/web/*/http://askmrsdof.tumblr.com/).

## Web Component

I was given the following example themes by the client:

* [oscarprgirl.tumblr.com](http://oscarprgirl.tumblr.com/)
* [anthropologie.tumblr.com](http://anthropologie.tumblr.com/)
* [katespadeny.tumblr.com](http://katespadeny.tumblr.com/)
* [alexandermcqueen.com](http://www.alexandermcqueen.com/mcq/en_US)
* [garancedore.fr](http://www.garancedore.fr/)
* [thecherryblossomgirl.com](http://www.thecherryblossomgirl.com/)

I noticed the following about these sites:

* The layout of the sites where either picture grid or textual columns.
* The colors where mainly black and white with one main color.
* Fashion sites place more of an emphasis on photography then text.
* The sites contain advertising in the sidebar.
* Some brands have the same theme for their shop as their blog, some dont.

This is the mockup that was provided by the client after out inital discussion.

<a href="{{ page.gallery.three.href }}"><img src="{{ page.gallery.three.src }}" alt="{{ page.gallery.three.alt }}"></a>

## Graphic Component

> If you could make a silhouette of the woman in the image, crop it a bit and just make the bow the blue from the powerpoint I gave you that would be great; or if you can keep the image the same, but the bow the blue we have that would be great as well. Idk thoughts? If you can give me some options that would be cool and of course remove the background too.I also found this silhouette of a girl, but would prefer the head to face left to the log, but again with a ribbon or bow in her hair.

Here where to two images provided:

<div class="thumbnails" style="margin-bottom:20px">
  {% for image in page.gallery.one %}
  <div class="thumbnail span{{ image.span }}">
    <a href="{{ image.href }}"><img src="{{ image.src }}" alt="{{ image.alt }}"></a>
  </div>
  {% endfor %}
</div>

This is what I created, I traced both raster images by hand in adobe illustrator with the pen tool.

<div class="thumbnails" style="margin-bottom:20px">
  {% for image in page.gallery.two %}
  <div class="thumbnail span{{ image.span }}">
    <a href="{{ image.href }}"><img src="{{ image.src }}" alt="{{ image.alt }}"></a>
  </div>
  {% endfor %}
</div>

{% comment %}

<div class="thumbnails" style="margin-bottom:20px">
  {% for image in page.gallery %}
  <div class="thumbnail span{{ image.span }}">
    <a href="{{ image.href }}"><img src="{{ image.src }}" alt="{{ image.alt }}"></a>
  </div>
  {% endfor %}
</div>

{% endcomment %}