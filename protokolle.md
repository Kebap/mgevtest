---
redirect_from: /verein/archiv/protokolle.shtml
show_archive: true
---

## Protokolle

{% for meeting in site.protokoll reversed %}
- [ {{ meeting.type }} vom {{ meeting.date | date: "%d.%m.%Y" }} in {{ meeting.location }}]({{ meeting.url }}){% endfor %}
{: class="liste"}

<aside>
<p>Bei der Gr&uuml;ndungsversammlung waren anwesend:<br />
   Bertram, Catweazle, Findulas, Fraggle, Imar, Jof, Kirk, Li, McTrinsic,
   Quillian, Rochus, Rumata, Ryne, Silvana, Toeter, Viper, Vrai, Wargon, Yendi.</p>
</aside>