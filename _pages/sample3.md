---
title:  "Example 3"
permalink: /sample3/
layout: single
sidebar:
  nav: samples
date:   2025-11-29 17:18:43 +0100
categories: jekyll update javascript
---


This is a notice
{: .notice #target}

<script>
  let hash = location.hash.substr(1);
  hash = decodeURIComponent(hash);
  hash = hash.replace("<", "");
  hash = hash.replace(">", "");
  let d = document.getElementById("target");
  d.innerHTML = hash;
</script>


```javascript
let hash = location.hash.substr(1);
hash = decodeURIComponent(hash);
hash = hash.replace("<", "");
hash = hash.replace(">", "");
let d = document.getElementById("target");
d.innerHTML = hash;
```

