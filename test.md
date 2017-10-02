---
layout: page
title: Test
permalink: /test/
---

<center><a href="https://yale-lily.github.io/"><img src="/lily-logo.png" alt="test image" width="20%" height="20%"></a></center>
 <header class="post-header">
    <h2 class="post-title">The Data Science Workshop on Computational Social Science</h2>
  </header> 



<h3 align="center">Friday, October 20, 2017</h3>
<h3 align="center">Luce Hall, 34 Hillhouse Avenue at Yale University</h3>
<h3 align="center"><a href="https://docs.google.com/forms/d/e/1FAIpQLSdXxc3x7TMrKzJq_2Ufc5mMpyiLBjd8JHLJayRFtHSdE2twSA/viewform">Register</a> Now!</h3>
## Location

The workshop will be held at the [Luce Hall](http://conferencesandevents.yale.edu/campus/venues/luce-hall) at Yale University. The address is 34 Hillhouse Ave, New Haven, CT 06511.

<table>
{% for talk in site.data.talks.talks %}


## Schedule
  <tr><td style="padding:10px">
{% if talk.image %}<img width="250px" src="{{talk.image}}"> {% endif %}
</td><td style="padding:10px">
{{talk.title}}
<br>
{{talk.speaker}}<br>
{{talk.affiliation}} <br>

{% if talk.abstract %}
<a class="btn btn-labeled btn-primary" href="#mycollapse2" data-toggle="collapse"> Abstract </a> {% endif %} 
<div style="max-width:400px" id="mycollapse2" class="collapse">
test
</div>
<br>

</td></tr>

{% endfor %}
</table>

<iframe width="700" height="350" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://www.google.com/maps/embed/v1/place?q=place_id:ChIJTxEsvLfZ54kRSmWXc78lmh0&key=AIzaSyC9I1jdJUkkDqPm8OXQlzPQcsVLM5juJkg" allowfullscreen></iframe>