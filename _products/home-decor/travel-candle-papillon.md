---
layout: product
title: Travel Candle - Papillon
item-id: travel-candle-papillon
image_path: ../../../images/home-decor/travel-candle-papillon.jpg
category: home-decor
permalink: /products/home-decor/travel-candle-papillon/
description: ""
price_usd: 21.47
price_ttd: 145
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