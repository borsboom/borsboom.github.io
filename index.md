---
layout: page
title: Emanuel Borsboom
tagline: My projects
---
{% include JB/setup %}

#### Some of my projects:

* [Vocoder](http://borsboom.github.io/vocoder) - Program that imposes vocal effects on a waveform
* [Current atlas tables](http://borsboom.github.io/current-atlas-tables) - Scripts to generate lookup tables for the the Current Atlas: Juan de Fuca Strait to Strait of Georgia 
* [Synth](http://borsboom.github.io/synth) - A Java-based software modular synthesizer
* [Babal](http://borsboom.github.io/babal) - A simple 3-D game based on Babal for HP48
* [Midi scripter](http://borsboom.github.io/midi-scripter) - Program to generate a MIDI file from simple commands in text files

See [my GitHub profile](https://github.com/borsboom).

#### Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
