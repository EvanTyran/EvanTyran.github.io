# EvanTyran.github.io
Testing testing 123

## My Projects
{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }}) - {{ post.date | date_to_string }}
{% endfor %}
