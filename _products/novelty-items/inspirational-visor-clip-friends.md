---
layout: product
title: Inspirational Visor Clip - Friends
item-id: inspirational-visor-clip-friends
image_path: ../../../images/novelty-items/inspirational-visor-clip-friends.jpg
category: novelty-items
permalink: /products/novelty-items/inspirational-visor-clip-friends/
description: "Friends Don't Let Friends Angel Visor Clip. An angelic reminder can go a lot further than you think! Our Friends Don't Let Friends Visor Clip is a great way to remind your loved ones to always drive safely. This Visor Clip features a stunning Angel that is reaching up to the stars."
price_usd: 12.45
price_ttd: 85.00
excerpt_separator: <!--more-->
---

<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold my-2 py-2 px-4 w-full snipcart-add-item" 
data-item-id="{{ page.item-id }}" 
data-item-price="{{page.price_usd}}"
data-item-url="{{ site.url }}/{{ page.category }}"
data-item-description="{{ page.description }}"
data-item-image="{{ page.image_path }}"
data-item-name="{{ page.title }}"
data-item-categories="{{ page.category }}">
${{ page.price_usd }} USD or ${{ page.price_ttd }} TTD
</button>

<!--more-->
<div class="flex flex-wrap">
  <div class="w-64 p-4 h-auto">
    <a data-fancybox="gallery" href="{{ page.image_path }}"><img src="{{ page.image_path }}"></a>
  </div>
  <div class="sm:flex-1">
    <p class="p-4 text-gray-700">
      {{ page.description }}
    </p>
  </div>
</div>