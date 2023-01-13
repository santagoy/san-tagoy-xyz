---
title: Nico's Road to Better Writing
type: docs
bookToc: false
---

# Nico's Road to Better Writing

---

## Marketing is insidious, which is why I made this site: partly for marketing myself.

Besides writing, I designed a number of Tabletop games: [**Letters of the Sky (2021)**](https://far-horizons-co-op.itch.io/sgd8) and [**The Moment Phantasm (2022)**](https://far-horizons-co-op.itch.io/anthology-2-1). Both epistolary games published in anthologies by The Far Horizons Co-op.

As for other things I've written in the scene, there's [**Blessed Art Thou (2022)**](https://spearwitch.com/products/violence-collection) also published in an anthology.

This is my journey to better writing. A catalog of my progress and an outlet as some creative online.

<!--
  This is the HTML block you need to insert wherever you want
  your webring to show up. By default, it is displayed exactly
  as it is styled on the host.

  The entries in the allow attribute(s) are security defaults.
  You're welcome to override them if you want, but it's best
  to leave them in place unless something is broken. For more
  info on them, see:
      https://www.w3schools.com/tags/tag_iframe.asp
  The only setting that *has* to remain in place is in the
  sandbox attribute; 'allow-top-navigation-by-user-activation'
  is what enables the iframe to send users to a member site or
  the list of members. The 'allow-same-origin' is required for
  the included script to work and set the styling correctly.
  The 'allow-scripts' attribute is only required if you are
  using the random member link.
-->
<iframe id="toroidal-iframe-other-cool-folks-nico"
        class="toroidal"
        frameBorder="0"
        allow="layout-animations 'none';
        unoptimized-images 'none';
        oversized-images 'none';
        sync-script 'none';
        sync-xhr 'none';
        unsized-media 'none';"
        allowfullscreen="false"
        allowpaymentrequest="false"
        sandbox="allow-top-navigation allow-same-origin allow-scripts"
        src="https://san-tagoy.xyz/toroidal/san-tagoy/" >
</iframe>

<!--
  You can put this script block wherever makes sense for your
  site; you might want it in your footer or pulled into a JS
  file, but if you want the iframe to configure correctly,
  you will need it *somewhere*.
-->
<script>
  // This function configures the iframe display so that it
  // looks okay after loading; this default implementation
  // will display the iframe to its actual size wherever
  // you put it in your site, themed exactly as it is on
  // the host.
  function configureToroidalIframe() {
    let iframeID = 'toroidal-iframe-other-cool-folks-nico'
    let navID    = 'toroidal-nav-other-cool-folks'
    let webringIframe = document.getElementById(iframeID);
    if (webringIframe != null) {
      let webringDoc = webringIframe.contentDocument;
      let webringNav = webringDoc.getElementById(navID);
      webringDoc.body.style.overflow = 'hidden';
      webringIframe.style.height = (webringNav.scrollHeight + 30) + 'px';
    } else {
      setTimeout(configureToroidalIframe, 100); 
    }
  }
  
  // When the window loads, the iframe configuration is called;
  // the implementation will retry until it is able to connect.
  window.onload = function() {
    configureToroidalIframe();
  }
</script>

<form
  action="https://buttondown.email/api/emails/embed-subscribe/san_tagoy"
  method="post"
  target="popupwindow"
  onsubmit="window.open('https://buttondown.email/san_tagoy', 'popupwindow')"
  class="embeddable-buttondown-form"
>
  <label for="bd-email">Subscribe to my newsletter</label>
  <input type="email" name="email" id="bd-email" />
  <input type="submit" value="I'd love to!" />
  <p>
    <a href="https://buttondown.email" target="_blank">Powered by Buttondown.</a>
  </p>
</form>

---

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />All works written in [Blog Posts]({{% ref "/posts/_index.md" %}}) are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
