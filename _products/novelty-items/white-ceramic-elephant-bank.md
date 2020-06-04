---
layout: product
title: White Ceramic Elephant Bank
item-id: white-ceramic-elephant-bank
image_path: ../../../images/novelty-items/white-ceramic-elephant-bank.jpg
category: novelty-items
permalink: /products/novelty-items/white-ceramic-elephant-bank/
description: "White elephant whimsical coin bank glazed ceramic, high gloss finish. Add a touch of personality to your home decor. Size: 6 x 3.5 x 5."
price_usd: 24.17
price_ttd: 165.00
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