---
marp: true
title: Product Documentation Presentation
author: Rahul Kumar
paginate: true
theme: default
---

<style>
section { font-family: "Inter", sans-serif; }
h1 { color: #0077cc; }
.email-box {
  font-size: 1.1rem; font-weight: bold;
  background: #eef7ff; padding: 10px 16px;
  border-left: 6px solid #0077cc; border-radius: 4px;
  display: inline-block;
}
</style>

# Product Documentation  
## Software Platform — Overview

<div class="email-box">Contact: 24f2001869@ds.study.iitm.ac.in</div>

---

![bg cover](images/product-bg.jpg)

# Product Architecture

Our platform follows a modular, scalable, cloud-native architecture.

---

# Algorithmic Complexity

### Time Complexity of Merge Sort

$$
T(n) = 2T \left(\frac{n}{2}\right) + O(n)
$$

Therefore:

$$
T(n) = O(n \log n)
$$

---

# Code Example

```javascript
export function computeHash(input) {
  return crypto.subtle.digest("SHA-256", new TextEncoder().encode(input));
}
