---
title:  "Example 2"
permalink: /sample2/
layout: single
sidebar:
  nav: samples
date:   2025-11-29 17:18:43 +0100
categories: jekyll update javascript
---


This is a notice
{: .notice #target}

<script>
  let url = URL.parse(location.toString());
  let params = url.searchParams;
  let p1 = params.get("p1");
  let p2 = params.get("p2");
  let d = document.getElementById("target");
  if (p1 && p2) {
    d.innerHTML = p1 + " " + p2;
  }
</script>


```javascript
let url = URL.parse(location.toString());
let params = url.searchParams;
let p1 = params.get("p1");
let p2 = params.get("p2");
let d = document.getElementById("target");
d.innerHTML = p1 + " " + p2;
```

