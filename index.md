---
layout: default
---

# About

Social Software Living Lab (S2L2) program aims to prepare students for responsible and ethical software development using modern and innovative techniques. Students act as problem solvers, using their skills to provide solutions for society.

## Motivation

S2L2 arises from the vision that society must engage in the development of software intended for social services by understanding their problems and participating in the process of creating and validating systems.

Another issue motivating the emergence of S2L2 is the disconnection between academia and industry in exploring scientific-technological solutions to scale software development. Methods and tools proposed in the scientific literature are often evaluated only experimentally in limited contexts. Empirical evaluations are essential for technology transfer, and this program seeks to conduct these evaluations in real-world software development contexts.

Additionally, the program seeks to improve students' preparation for the software development market, particularly regarding software's social role.

## Qualification and Training

Online and in-person training is offered, tailored to students' needs and ongoing projects. The S2L2 leverages distance learning platforms and practical on-demand courses, including emerging technologies like web development and mobile applications.

## Projects Implementation

The adopted methodology integrates agile practices, Design Thinking, and Socially-Aware Design to ensure user-centered development and the delivery of functional software. Project execution includes mentoring by volunteer professionals and empirical-experimental studies to evaluate new technologies.

Each project results in the delivery of functional software and associated documentation, ready for operational use. The accumulated learning is disseminated through scientific publications, feedback in training sessions, and promotional material to attract new projects and collaborators.

## Team

The team includes undergraduate and graduate students from Unicamp, IT market volunteers, and collaborating professors from various fields. All members are committed to a Code of Conduct that promotes best development practices, ethics, social responsibility, and diversity.

<br>
# Projects

<div class="posts">
  {% for post in site.posts %}
    <div class="post-preview">
      <a href="{{ post.url | absolute_url }}">
        <h2 class="post-title">{{ post.title }}</h2>
        <p class="post-excerpt">{{ post.excerpt }}</p>
      </a>
      <p class="post-meta">Publicado em {{ post.date | date: "%B %d, %Y" }}</p>
    </div>
    <hr>
  {% endfor %}
</div>
