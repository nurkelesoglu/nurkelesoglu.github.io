---
layout: single
title: "Productivity"
permalink: /productivity/
author_profile: true
---

Things I make outside of research.

Drone videography
======

I have been a drone operator since **August 2020**. I film landscapes, coastlines and cities from the air and publish the edited clips on my [YouTube channel](https://www.youtube.com/@nurkelesoglu).

<div class="video-embed" data-embed="https://www.youtube.com/embed/videoseries?list=PLB8lgZX0xT95ejCd9PK711UOIypj__2Jc&autoplay=1">
  <button type="button" class="video-embed__poster" aria-label="Play the drone videos playlist">
    <img src="/images/drone-playlist.jpg" alt="Aerial view of Lindos, Rhodes, Greece" loading="lazy">
    <span class="video-embed__play" aria-hidden="true"><i class="fas fa-play"></i></span>
    <span class="video-embed__caption">Drone videos · YouTube playlist</span>
  </button>
</div>

<p class="video-embed__links">
  <a class="btn btn--primary" href="https://www.youtube.com/watch?v=-4wgFdQBcQI&list=PLB8lgZX0xT95ejCd9PK711UOIypj__2Jc"><i class="fab fa-fw fa-youtube"></i> Watch the playlist on YouTube</a>
</p>

<script>
  document.querySelectorAll('.video-embed').forEach(function (box) {
    var poster = box.querySelector('.video-embed__poster');
    if (!poster) { return; }
    poster.addEventListener('click', function () {
      var iframe = document.createElement('iframe');
      iframe.src = box.getAttribute('data-embed');
      iframe.title = 'Drone videos playlist';
      iframe.allow = 'accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share';
      iframe.setAttribute('allowfullscreen', '');
      iframe.setAttribute('referrerpolicy', 'strict-origin-when-cross-origin');
      box.replaceChild(iframe, poster);
    });
  });
</script>
