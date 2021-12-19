# Projects

## [Pollbot](https://top.gg/bot/795890638318600222)
> A Discord bot to do ranked choice polls.

{% for project in site.projects %}
  <h2>
    <a href="{{ project.url }}">
      {{ project.name }}
    </a>
  </h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}