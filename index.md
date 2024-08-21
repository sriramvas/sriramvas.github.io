---
layout: default
---

I'm **Sriram**, and am based in Chennai. Welcome to my home on the interweb!

Professionally, am a startup operator helping out teams with marketing & strategy. The rest of my time, am traveling, nerding out on philosophy, or playing football with the gang.

Feel free to drop a hi on [X/twt](https://x.com/sriramvas) if you want to chat :)

## Work

[Socket](https://x.com/SocketProtocol) --- lead marketing and comms to help spread the chain abstraction gospel.

[Bungee](https://x.com/BungeeExchange) --- shitposting and growing Bungee into the #1 bridge for DeFi

In my past life I was contributing at [IndexCoop](https://indexcoop.com/), [SuperTeam](https://superteam.fun/) and education NGOs.


## Posts

{% for post in site.posts %}

{{ post.date | date: "%b '%y" }} [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
