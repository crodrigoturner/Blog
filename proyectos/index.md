---
layout: page
title: Proyectos
id: proyectos
ref: proyectos
toc: false
lang: es
---

<h3>Trayectoria profesional y formación</h3>

Echale un vistazo a mi <a href="/cv/">cv</a>.
<br/> Visita mi perfil en <a href="https://www.linkedin.com/in/crodrigoturner/" target="_blank">Linkedin</a>.

<H3>Proyectos en curso</h3>

<ul >
{% for proyecto in site.proyectos %}
<li><a href="{{ proyecto.url }}">{{ proyecto.title }}<span class="excerpt">{{proyecto.excerpt}}</span></a></li>
{% endfor %}  
</ul>



