---
layout: post_callouts
title: People
bottom_callouts: people_callouts
---

<div class="columns is-multiline">
  {% for person in site.team %}
  <div class="column is-one-third-tablet is-one-quarter-desktop">
    <div class="card">
      
      <!-- Portrait Image -->
      <div class="card-image">
        <a href="{{ person.url | relative_url }}">
          <figure class="image is-4by5">
            <img src="{{ person.image | relative_url }}" alt="{{ person.title }}">
          </figure>
        </a>
      </div>
      
      <!-- Name and Role -->
      <div class="card-content">
        <div class="content has-text-centered">
          <p class="title is-5">
            <a href="{{ person.url | relative_url }}">{{ person.title }}</a>
          </p>
          <p class="subtitle is-6">{{ person.role }}</p>
        </div>
      </div>
      
    </div>
  </div>
  {% endfor %}
</div>

<!-- ## SETCA Spring 2022 -->
<!-- ![Conf Pic 1]\(/assets/img/group/SETCA_2022.jpeg) -->

<!-- ## Group Winter 2021 -->
<!-- ![Group Pic 2]\(/assets/img/group/CCQC_2021.jpg) -->

<!-- ## Virtual Group Summer 2020 -->
<!-- ![Group Pic 1]\(/assets/img/group/CCQC_2020.png) -->
