---
title:  "Example 1"
permalink: /sample1/
layout: single
sidebar:
  nav: samples
#date:   2025-11-29 17:18:43 +0100
#categories: jekyll update javascript
---

Hello


<script>
    var hash = location.hash;
    var decoded = decodeURIComponent(hash.substring(1));
    var message = "Hello " + decoded + " there!";
    document.write(message);
</script>


```javascript
var hash = location.hash;
var decoded = decodeURIComponent(hash.substring(1));
var message = "Hello " + decoded + " there!";
document.write(message);
```

