# Contributors:
{% for s in site.stu %}
  <p>>><img src="{{s.image}}">@{{ s.user }} ({{ s.name }})</p>
  <p>&emsp;>>{{ s.content | markdownify }}</p>
{% endfor %}
