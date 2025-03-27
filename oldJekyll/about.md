---
layout: about
title: À propos
accent_color: '#E04750'
accent_image:
  background: '#2D2D36'
  overlay:    false
accent_image:          /assets/img/remi-houda.jpg
menu: true
order: 4
---


{% for staff_data in site.data.staff_list | sort "end" | reverse %}
# L'équipe {{ staff_data.date }}
<div class="container">
{% for staff_member in staff_data.staff_members %}
{% assign image_basename = staff_member.image %}
{% if image_basename == "" or image_basename == nil %}
{% assign image_basename = "UniMakersMemberNoImage.png" %}
{% endif %}
{% assign image_url = image_basename | prepend: "/assets/img/membre/" %}
<div class="image-container">
<img src="{{ image_url }}" alt="{{ staff_member.name }}">
<p>{{ staff_member.name }}</p>
<p>{{ staff_member.post }}</p>
</div>
{% endfor %}
</div>
{% endfor %}


<!-- # L'équipe 2024- Mars 2025

<div class="container">

  <div class="image-container">
    <img src="/assets/img/membre/Dylan_Looij.jpg" alt="Dylan Looij">
    <p>Dylan Looij</p>
    <p>Directeur</p>
  </div>
  
  <div class="image-container">
    <img src="/assets/img/membre/Aurelien.png" alt="Aurelien Sézille">
    <p>Aurelien Sézille</p>
    <p>Directeur</p>
  </div>
  
  <div class="image-container">
    <img src="/assets/img/membre/PA.jpg" alt="Ambre Moreau">
    <p>Ambre Moreau</p>
    <p>Directrice</p>
  </div>
  
  <div class="image-container">
    <img src="/assets/img/membre/PA.jpg" alt="Mathieu Lardereau">
    <p>Mathieu Lardereau</p>
    <p>Reponsable Sponosoring</p>
  </div>

  <div class="image-container">
    <img src="/assets/img/membre/PA.jpg" alt="Clémence Leleu">
    <p>Clémence Leleu</p>
    <p>Chargé de projet Audiovisuel</p>
  </div>

</div> 



# L'équipe 2023-2024

<div class="container">
  <div class="image-container">
    <img src="/assets/img/membre/Dylan_Looij.jpg" alt="Dylan Looij">
    <p>Dylan Looij</p>
    <p>Directeur Technique</p>
  </div>
  
  <div class="image-container">
    <img src="/assets/img/membre/Quentin_Fache.png" alt="Quentin Fache">
    <p>Quentin Fache</p>
    <p>Chargé des Sponsors et des finances</p>
  </div>
  
  <div class="image-container">
    <img src="/assets/img/membre/PA.jpg" alt="PA">
    <p>Pierre-Alex Bianchi</p>
    <p>Chargé de la Communication</p>
  </div>
</div> 

# L'équipe 2022-2023

<div class="container">
  <div class="image-container">
    <img src="/assets/img/membre/Remi_Lacombe.png" alt="Rémi Lacombe">
    <p>Rémi Lacombe</p>
    <p>Directeur Pôle Robotique</p>
  </div>
  
  <div class="image-container">
    <img src="/assets/img/membre/Bixente_Lecadieu.png" alt="Bixente Lecadieu">
    <p>Bixente Lecadieu</p>
    <p>Directeur pôle Makerspace</p>
  </div>
  
  <div class="image-container">
    <img src="/assets/img/membre/Teva_Houziaux.png" alt="Teva Houziaux">
    <p>Teva Houziaux</p>
    <p>Directeur pôle Modélisme</p>
  </div>
</div>  -->


# Le branding Kit d'Unimakers

[BrandingKit](assets/Files/Branding-kit.zip)


[blog]: https://qwtel.com/hydejack/blog/
[portfolio]: https://qwtel.com/hydejack/variations/
[resume]: https://qwtel.com/hydejack/resume/
[download]: https://qwtel.com/download/
[welcome]: https://qwtel.com/hydejack/
[forms]: https://qwtel.com/hydejack/forms-by-example/

[feat]: #features
[news]: #newsletter-subscription-box
[syntax]: #syntax-highlighting
[latex]: #latex-math-blocks

[license]: LICENSE.md
[pro]: licenses/PRO.md
[docs]: docs/7.5.0/index.md

[kit]: https://github.com/qwtel/hydejack-starter-kit/archive/v7.5.0.zip
[src]: https://github.com/qwtel/hydejack
[gem]: https://rubygems.org/gems/jekyll-theme-hydejack
[buy]: https://app.simplegoods.co/i/AQTTVBOE

[gpss]: https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fqwtel.com%2Fhydejack%2F
[wiki]: https://github.com/qwtel/hydejack/blob/master/docs/7.5.0/index.md
[pdf]: https://github.com/qwtel/hydejack/releases/download/v7.5.0/Documentation._.Hydejack.pdf
[hy-push-state]: https://qwtel.com/hy-push-state/
[hy-drawer]: https://qwtel.com/hy-drawer/
[rouge]: http://rouge.jneen.net
[katex]: https://khan.github.io/KaTeX/
[tinyletter]: https://tinyletter.com/

*[FLIP]: First-Last-Invert-Play. A coding technique to achieve performant page transition animations.

