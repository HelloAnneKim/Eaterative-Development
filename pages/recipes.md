---
layout: page
title: "All the Yummy Yummies"
teaser: "Here are all the recipes"
categories: gallery, recipes, 
  -
tags: recipes
  -
#
# Gallery
#
gallery:
    - image_url: gallery-example-1.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-2.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-3.jpg
      caption: Great images by Unsplash.com
#
# Styling
#
image:
 thumb:
#
# Metainformation & Customization
#
meta_description:
permalink: /recipes/
---
Something here
{% include gallery %}

<ul class="post-list">
{% for post in site.posts %}
  {% if post.categories contains 'recipe' %}
    <li>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

      <h2>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title | escape }}</a>
      </h2>
    </li>
  {% endif %}
{% endfor %}
</ul>
