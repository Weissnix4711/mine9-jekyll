---
layout: page
title: Servers
permalink: /servers/
---

Here you can find information for all the games, and individual servers, we host.

{% for server in site.servers %}
* [{{server.title}}]({{server.url}})
{% endfor %}

If you would like to suggest a new server type, or game, you can do so in our [discord server](/about).
