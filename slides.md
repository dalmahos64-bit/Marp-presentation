---
marp: true
title: "Product Documentation Presentation"
description: "Technical writer documentation using Marp"
paginate: true
theme: custom-theme
class: lead
---

<style>
/* Custom Theme Definition */
section {
  font-family: 'Segoe UI', sans-serif;
}

h1 {
  color: #2c3e50;
}

.custom-box {
  border: 3px solid #3498db;
  padding: 16px;
  border-radius: 12px;
  background: #ecf6ff;
  font-size: 1.1em;
}
</style>

<!-- Custom Theme Registration -->
<style>
:root {
  --bg-color: #ffffff;
  --text-color: #111111;
}
</style>

# Product Documentation  
### Using Marp for Maintainable Technical Docs  
**Author:** 23f2003561@ds.study.iitm.ac.in

---

# Why Marp?
- Markdown-based  
- Great for version control (Git)  
- Easy conversion to HTML/PDF/PPTX  
- Highly customizable (themes, CSS, directives)

---

<!-- Background Image Slide -->
<!-- Replace with your own image URL later -->
![bg](https://images.unsplash.com/photo-1518770660439-4636190af475)

# Documentation Architecture  
### With a Clean Background Image

Marp allows backgrounds via slide-level directives or image syntax.

---

# Custom Styling Example

<div class="custom-box">
This is a *custom-styled box* using inline CSS  
inside the `slides.md` file.  
Great for warnings, notes, and highlights.
</div>

---

# Algorithmic Complexity

We can include mathematical notation using KaTeX:

### Example: Merge Sort  
\[
T(n) = 2T\left(\frac{n}{2}\right) + O(n)
\]

### Resulting complexity:
\[
T(n) = O(n \log n)
\]

---

# Additional Features
- Page numbers enabled  
- Custom theme defined inline  
- Ready for GitHub + CI export  
- Version-controlled documentation workflow

---

# Thank You  
For questions, email: **23f2003561@ds.study.iitm.ac.in**

