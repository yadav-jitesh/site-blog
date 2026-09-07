---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title : Jitesh Yadav
---

# Hello World

I build small web projects and publish them here.

This site is the first version of my GitHub Pages page. I use it for notes, project write-ups, and a short bio.

## What you will find

- Project updates
- Short technical notes
- Links to my work on GitHub
- [Posts]({{ "/about/" | relative_url }})

## Featured project

**[Directroy Boiler Plate](https://github.com/yadav-jitesh/directory-site)**  
One sentence: what it does and who it is for.
## Blog

{% raw %}{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }})  
  <small>{{ post.date | date: "%b %-d, %Y" }}</small>
{% endfor %}{% endraw %}

## Featured Digital Product

**[Solo Operator: Security Kit](https://beatslofi.gumroad.com/l/sosk)**  
One sentence: what it does and who it is for.

## Contact

- GitHub: [YADAV-JITESH](https://github.com/yadav-jitesh)
- Email: [YADAV-JITESH]yadav.jitesh@gmail.com

## More

- [About this site]({{ "/about/" | relative_url }})