---
layout: wide_page
screenshots: 
 - /images/old_screenshot_1.png
 - /images/old_screenshot_2.png
 - /images/old_screenshot_3.png
 - /images/old_screenshot_4.png
 - /images/old_screenshot_5.png
 - /images/old_screenshot_6.png
---
{% for shot in page.screenshots %}
<a href="{{shot}}">
  <img src="{{shot}}"/>
</a>
{% endfor %}

