---
layout: post
title:  "Testing insert JavaScript"
date:   2025-11-29 17:18:43 +0100
categories: jekyll update javascript
code: >
    var hash = location.hash;
    var decoded = decodeURIComponent(hash.substring(1));
    var message = "Hello " + decoded + " there!";
    document.write(message);

---

Hello


<script>
    var hash = location.hash;
    var decoded = decodeURIComponent(hash.substring(1));
    var message = "Hello " + decoded + " there!";
    document.write(message);
</script>


```JavaScript
var hash = location.hash;
var decoded = decodeURIComponent(hash.substring(1));
var message = "Hello " + decoded + " there!";
document.write(message);
```

