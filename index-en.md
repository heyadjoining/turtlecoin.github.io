---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit jekyll-theme-simple-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
permalink: /index.html
header:
  image: /assets/img/home-header.png
tagline: > # this means to ignore newlines until "repository:"
  TurtleCoin is a fun, community-driven, CryptoNote based blockchain
  focused on community, user experience and pizza.
excerpt: >
  TurtleCoin is a fun, community-driven, CryptoNote based blockchain
  focused on community, user experience and pizza.
homepage:
  repository_url: https://github.com/turtlecoin
  release_url: https://github.com/turtlecoin/turtlecoin/releases/latest
ref: home
lang: en
---

  TurtleCoin is a fun, community-driven, CryptoNote based blockchain
  focused on community, user experience and pizza.
<h2>Latest Announcements</h2>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="articles" %}

---
