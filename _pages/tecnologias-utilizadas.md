---
permalink: /tecnologias
title: Tecnologias Utilizadas
layout: landing
image: assets/images/ferramentas.jpg
nav_menu: true
show_on_tile: true
menu_position: 2
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
    <div class="row">
      {% for tecnology in site.data.tecnologies %}
        <div class="6u 12u$(medium) tecnologies">
          <div class="box">
            <div class="row">
              <div class="3u 12u$(medium)">
                <img src="{{ site.baseurl }}/assets/images/{{ tecnology.image }}" />
              </div>
              <div class="9u 12u$(medium) tecnology-name">
                <h2>{{ tecnology.name }}</h2>
              </div>
            </div>
            <div class="row">
              <div class="12u docs-link align-center">
                <a href="{{ tecnology.docs_link }}" class="button fit" target="_blank">
                  Documentação
                </a>
              </div>
            </div>
          </div>
        </div>
      {% endfor %}
    </div>
	</div>
</section>

</div>
