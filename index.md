# Yuzulia-Document

{% for post in site.pages %}
{% if post.title and post.url != "/" %}
- [{{ post.title }}](.{{ post.url }})

{% endif %}
{% endfor %}
