# Yuzulia-Document

{% for post in site.pages %}
{% if post.title or post.url != '/' %}
- [{{ post.title }}](.{{ post.url }})

{% endif %}
{% endfor %}
