---
layout: default
---

# Hello
I'm a Staff Scientist at Applied Ocean Sciences.

From 2015-2019, I was a staff scientist at Ocean Acoustical Services and Instrumentation Systems, Inc.

From 2014-2015, I studied ocean acoustic modeling at Scripps Institution of Oceanography, with Bill Kupermann as advisor.

From 2012-2014, I was a member of the [Northwest Electromagnetics and Acoustics Research Laboratory](http://nearlab.ece.pdx.edu).

From 2008-2012, I was a member of the Acoustics Research Group and ASA student chapter at Brigham Young University.

From 2007-2009, I was Assistant to the General Manager and a Producer at Classical 89, KBYU-FM.


## Blog Posts
<ul class="posts">
{% for post in site.posts %}
<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>


## Current Projects
<ul class="posts">

</ul>

## Past Projects
<ul class="posts">
  <li><a href="/nabebimo.html">2013 National Acoustic Beamformer Building Month</a></li>
  <li><a href="http://github.com/psas/launch-tower-comm">PSAS Launch Tower Comm</a></li>
</ul>


## Computing Notes
<ul class="posts">
{% for note in site.notes %}
<li><a href="{{ note.url }}">{{ note.title }}</a></li>
{% endfor %}
</ul>

