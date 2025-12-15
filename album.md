---
layout: single
title: "風景相簿"
permalink: /album/
classes: wide
---

{% assign album = site.data.album %}
{% include banner-carousel.html slides=album.banner %}

歡迎來到風景相簿，以下收錄了每張照片與對應的大圖連結，點擊任意縮圖即可放大欣賞。

{% include gallery gallery=album.gallery caption="點擊圖片可開啟燈箱檢視。" %}
