---
title: "Optima Group - Team"
layout: gridlay
excerpt: "Optima Group: Team members"
sitemap: false
permalink: /team/
---

# Group Members

 **We are  looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**


Jump to [staff](#staff), [master and bachelor students](#master-and-bachelor-students), [alumni](#alumni), [administrative support](#administrative-support), [lab visitors](#lab-visitors).

## Advisors
{% assign number_printed = 0 %}
{% for member in site.data.staffs %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4><a href="{{ member.url }}">{{ member.name }}</a></h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_topic == 1 %}
  <li> {{ member.topic1 }} </li>
  {% endif %}

  {% if member.number_topic == 2 %}
  <li> {{ member.topic1 | markdownify}} </li>
  <li> {{ member.topic2 | markdownify}} </li>
  {% endif %}

  {% if member.number_topic == 3 %}
  <li> {{ member.topic1 }} </li>
  <li> {{ member.topic2 }} </li>
  <li> {{ member.topic3 }} </li>
  {% endif %}

  {% if member.number_topic == 4 %}
  <li> {{ member.topic1 }} </li>
  <li> {{ member.topic2 }} </li>
  <li> {{ member.topic3 }} </li>
  <li> {{ member.topic4 }} </li>
  {% endif %}

  {% if member.number_topic == 5 %}
  <li> {{ member.topic1 }} </li>
  <li> {{ member.topic2 }} </li>
  <li> {{ member.topic3 }} </li>
  <li> {{ member.topic4 }} </li>
  <li> {{ member.topic5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Postdoctoral Researchers
{% assign number_printed = 0 %}
{% for member in site.data.postdoctoral_researchers %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4><a href="{{ member.url }}">{{ member.name }}</a></h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_topic == 1 %}
  <li> {{ member.topic1 }} </li>
  {% endif %}

  {% if member.number_topic == 2 %}
  <li> {{ member.topic1 | markdownify}} </li>
  <li> {{ member.topic2 | markdownify}} </li>
  {% endif %}

  {% if member.number_topic == 3 %}
  <li> {{ member.topic1 }} </li>
  <li> {{ member.topic2 }} </li>
  <li> {{ member.topic3 }} </li>
  {% endif %}

  {% if member.number_topic == 4 %}
  <li> {{ member.topic1 }} </li>
  <li> {{ member.topic2 }} </li>
  <li> {{ member.topic3 }} </li>
  <li> {{ member.topic4 }} </li>
  {% endif %}

  {% if member.number_topic == 5 %}
  <li> {{ member.topic1 }} </li>
  <li> {{ member.topic2 }} </li>
  <li> {{ member.topic3 }} </li>
  <li> {{ member.topic4 }} </li>
  <li> {{ member.topic5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Postgraduate Students
{% assign number_printed = 0 %}
{% for member in site.data.students_postgraduate %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4><a href="{{ member.url }}">{{ member.name }}</a></h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_topic == 1 %}
  <li> {{ member.topic1 }} </li>
  {% endif %}

  {% if member.number_topic == 2 %}
  <li> {{ member.topic1 | markdownify}} </li>
  <li> {{ member.topic2 | markdownify}} </li>
  {% endif %}

  {% if member.number_topic == 3 %}
  <li> {{ member.topic1 }} </li>
  <li> {{ member.topic2 }} </li>
  <li> {{ member.topic3 }} </li>
  {% endif %}

  {% if member.number_topic == 4 %}
  <li> {{ member.topic1 }} </li>
  <li> {{ member.topic2 }} </li>
  <li> {{ member.topic3 }} </li>
  <li> {{ member.topic4 }} </li>
  {% endif %}

  {% if member.number_topic == 5 %}
  <li> {{ member.topic1 }} </li>
  <li> {{ member.topic2 }} </li>
  <li> {{ member.topic3 }} </li>
  <li> {{ member.topic4 }} </li>
  <li> {{ member.topic5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Master and Bachelor Students
{% assign number_printed = 0 %}
{% for member in site.data.students_master_and_bachelor %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4><a href="{{ member.url }}">{{ member.name }}</a></h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_topic == 1 %}
  <li> {{ member.topic1 }} </li>
  {% endif %}

  {% if member.number_topic == 2 %}
  <li> {{ member.topic1 | markdownify}} </li>
  <li> {{ member.topic2 | markdownify}} </li>
  {% endif %}

  {% if member.number_topic == 3 %}
  <li> {{ member.topic1 }} </li>
  <li> {{ member.topic2 }} </li>
  <li> {{ member.topic3 }} </li>
  {% endif %}

  {% if member.number_topic == 4 %}
  <li> {{ member.topic1 }} </li>
  <li> {{ member.topic2 }} </li>
  <li> {{ member.topic3 }} </li>
  <li> {{ member.topic4 }} </li>
  {% endif %}

  {% if member.number_topic == 5 %}
  <li> {{ member.topic1 }} </li>
  <li> {{ member.topic2 }} </li>
  <li> {{ member.topic3 }} </li>
  <li> {{ member.topic4 }} </li>
  <li> {{ member.topic5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Alumni

{% assign number_printed = 0 %}
{% for member in site.data.alumni_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4 href="{{ member.url }}">{{ member.name }}</h4>
  <i>{{ member.duration }} <br> Role: {{ member.info }}</i>
  <ul style="overflow: hidden">

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Visitors
<div class="row">
<div class="col-sm-6 clearfix">
{% for member in site.data.visitors %}
{{ member.name }}
{% endfor %}
</div>
</div>

## Former visitors, BSc/ MSc students
<div class="row">

<div class="col-sm-4 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Master students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Bachelor Students</h4>
{% for member in site.data.alumni_bsc %}
{{ member.name }}
{% endfor %}
</div>

</div>


## Stuffs & Administrative Support
<a href="mailto:Rijsewijk@Physics.LeidenUniv.nl">Rearch Assistant XXX</a> is helping us with XXX topic.
<a href="mailto:Rijsewijk@Physics.LeidenUniv.nl">Academic Secretary XXX</a> is helping us (and other groups) with administration.
