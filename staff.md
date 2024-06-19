---
layout: page
title: Staff
nav_order: 4
---

# Tuskegee Scholars Staff

{: .mb-2}
<div>
{% assign instructors = site.staffers | where: 'role', 'Faculty Director' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>
</div>

<div>
{% assign instructors = site.staffers | where: 'role', 'Bootcamp Facilitator' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>
</div>

<div>
{% assign instructors = site.staffers | where: 'role', 'Bootcamp Facilitator/Seminar Assistant' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>
</div>

<div>
{% assign instructors = site.staffers | where: 'role', 'Seminar Assistant' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>
</div>

<div>
{% assign instructors = site.staffers | where: 'role', 'Data C88C Academic Facilitator' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>
</div>
