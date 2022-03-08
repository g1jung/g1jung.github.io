---
layout: page
title: About Me
permalink: /about/
weight: 3
---

<style type="text/css">
.image-left {
	display: block; 
	padding-right: 14px;
	float: left;
}
</style>

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

---
<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

---

### **Education**

![DigiPen logo](/assets/aboutme/DigiPen_Logo.jpg){: .image-left }
BS, **DigiPen Institute of Technology** 2015 - 2022
Computer Science and Game Design
<br>
<br>

---

### **Experience**
<div class="row">
{% include about/timeline.html %}
</div>