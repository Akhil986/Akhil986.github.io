---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: prof_pic.jpeg
  image_circular: false # crops the image to make it circular
  #more_info: >
    # <p>555 your office number</p>
    #<p>123 your address street</p>
    #<p>Your City, State 12345</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

**About me**: I am currently pursuing a Bachelor’s degree in Computer Science at the University of Colorado Boulder. I am interested in pursuing Machine Learning and robotics, which I plan to explore in upcoming semesters.

I have worked in HackCU as a Marketing Manager for a couple of months. Through my coursework and projects, I have gained experience in backend development by taking a Databases class amd Intro to sofware Dev. I have also explored my interest in ML by taking classes such as Intro to AI and Data Science.

Outside of studying ,I like meeting people making friends. In my free time I like playing video games; I have played almost all Pokémon games, and recently got into shooter games such as Valorant and Deadlock, and also started playing Dark Souls and Minecraft. I also love watching anime and reading manga.

## Projects

<div class="projects">
  <div class="row row-cols-1 row-cols-md-2 justify-content-center">

    {% assign sorted_projects = site.projects | sort: "importance" %}

    {% for project in sorted_projects limit:2 %}
      <div class="col-md-5">
        {% include projects.liquid %}
      </div>
    {% endfor %}

  </div>
</div>


<div style="display:flex; justify-content:center; gap:30px; margin-top:30px; font-size:28px;">

  <!-- GitHub -->
  <a href="https://github.com/Akhil986" target="_blank" style="color:inherit; text-decoration:none;">
    <i class="fab fa-github"></i>
  </a>

  <!-- LinkedIn -->
  <a href="https://linkedin.com/in/YOUR-LINK" target="_blank" style="color:inherit; text-decoration:none;">
    <i class="fab fa-linkedin"></i>
  </a>

  <!-- Email -->
  <a href="mailto:your@email.com" style="color:inherit; text-decoration:none;">
    <i class="fas fa-envelope"></i>
  </a>

</div>


