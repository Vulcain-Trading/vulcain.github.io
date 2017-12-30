{{ site.lang }}
{% if site.lang == "fr" %} 
  {% include index_fr.md %} 
{% else %} 
  {% include index_en.md %}
{% endif %}

