---
layout: tailwind
title: Customizable Books
permalink: /customizable-books/
---

<div class="container mx-6 mt-6 p-8 mx-auto">
<h1 class="text-center text-2xl text-blue-700 tracking-wider">Customizable Books</h1>
</div>

<div class="flex flex-wrap min-w-0 max-w-full lg:px-16 p-4 justify-evenly">
  {% assign custom-books = site.products | where: "categories", "custom-books" %}
  {% for product in custom-books %}
  <div class="w-64 px-3 bg">
    <div class="bg-white rounded-lg my-4 overflow-hidden border shadow-md">
      <div>
      <a data-fancybox="gallery" href="{{ product.image_path }}"><img class="h-48 w-full object-cover object-top lozad image-to-load-first" src="{{ product.image_path }}" data-src="{{ product.image_path }}"></a>
      </div>
      <div>
        <div>
          <h3 class="text-sm text-gray-700 -m-2">{{ product.excerpt }}</h3>
        </div>
        <h1 class="font-semibold text-lg m-4 text-gray-900 leading-tight truncate"><a href="{{ product.url }}">{{ product.title }}</a></h1>
        <!--<h2 class="text-xs m-4 text-gray-500 uppercase tracking-wide">{{ product.categories }}</h2>-->
        <h3 class="text-xs text-gray-500 m-4 truncate">{{ product.description }}</h3>
      </div>
    </div>
  </div>
{% endfor %}
</div>