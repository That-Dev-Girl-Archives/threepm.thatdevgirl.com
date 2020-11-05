---
permalink: "/color-palette/"
layout: page
title: Color Palette | That Dev Girl
---

<section class="page-title" aria-label="Primary plugin information">
  <div class="page-title-inner">
    <div class="container">
      <h1>Color Palette</h1>

      <p>
        <a href="http://wordpress.org/plugins/color-palette/" class="btn on-blue">
          <span class="fa fa-download"></span> Download from WordPress
        </a>
        <a href="https://github.com/thatdevgirl/wordpress-color-palette" class="btn on-blue">
          <span class="fa fa-github"></span> View on GitHub
        </a>
      </p>

      <p class="description">
        This WordPress plugin adds a Color Palette block to the post editor, so content editors can easily list colors on branding and style guide pages.
      </p>
    </div>
  </div>
</section>

<section class="page-documentation" aria-label="Plugin details">
  <h2>Features</h2>

  <p>
    The Color Palette block displays a group of colors on your page. The block
    starts with 3 individual Color blocks, but you can add additional blocks or
    remove excess blocks as needed.
  </p>

  <p>
    Give each color block a color using the selector in the Inspector Panel on
    the right-hand side of the editor, give your color a name, and you are done!
  </p>

  <p>
    Each color in the palette will display a swatch of the selected color, the
    given color name, as well as the Hex, RGB, and CMYK values for that color
    <em>(optional)</em>.
  </p>

  <p>
    If you need to use the same color palette on multiple pages or posts, simply
    save the Color Palette block with all of your colors as a reusable block
    through the editor.
  </p>

  <h2>Palette color block styles</h2>

  <p>
    You can select the "Color block style" inside the Color Palette block by
    using the options in the Inspector Panel. The style options include:
  </p>

  <ul>
    <li>
      <b>Basic card:</b> Each color is displayed in a rectangular card with
      minimal additional styles. This option is the easiest to override in your
      theme styles.
    </li>
    <li>
      <b>Stylized card:</b> Each color is displayed in a rectangular card, just
      like the basic card, but with a bit more design added to it.
    </li>
    <li>
      <b>Circle:</b> Each color is displayed as a circle of color, with the name
      and color values centered underneath the circle of color.
    </li>
  </ul>

  <h2>Color code options</h2>

  <p>
    Inside the Color Palette block, you can select which color codes (Hex, RGB,
    or CMYK) should be hidden on the page. These options are in the Inspector
    Panel and apply to <em>all</em> color blocks inside the palette.
  </p>
  
  <h2>Screenshots</h2>

  <figure>
    <img src="{{site.images}}/color-palette-screenshot-1.jpg" alt="The Color Palette block in the post editor.">
    <figcaption>The Color Palette block in the post editor.</figcaption>
  </figure>

  <figure>
    <img src="{{site.images}}/color-palette-screenshot-2.jpg" alt="The Color Palette block in the front-end, displaying the colors as circles." />
    <figcaption>The Color Palette block in the front-end, displaying the colors as circles.</figcaption>
  </figure>

  <figure>
    <img src="{{site.images}}/color-palette-screenshot-3.jpg" alt="The Color Palette block in the front-end, displaying the colors as stylized cards." />
    <figcaption>The Color Palette block in the front-end, displaying the colors as stylized cards.</figcaption>
  </figure>
</section>

{% include block-donate.html %}
