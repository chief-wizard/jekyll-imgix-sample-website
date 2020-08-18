---
layout: post
title:  "Sample Post"
date:   2020-08-18 22:38:23 +0200
---

<img
  srcset="{{ '/unsplash/pineneedles.jpg' | imgix_url: w: 800, h: 600 }} 1x,
          {{ '/unsplash/pineneedles.jpg' | imgix_url: w: 800, h: 600, dpr: 2 }} 2x,
          {{ '/unsplash/pineneedles.jpg' | imgix_url: w: 800, h: 600, dpr: 3 }} 3x"
  src="{{ '/unsplash/pineneedles.jpg' | imgix_url: w: 800, h: 600 }}"
/>
