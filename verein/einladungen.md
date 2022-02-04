---
redirect_from: /verein/archiv/einladungen.shtml
show_archive: true
---

## Einladungen

Hier sind die Einladungen zu den einzelnen Mitgliederversammlungen des Vereins - soweit noch vorhanden - archiviert.

{% for meeting in site.einladung reversed %}
- [ Einladung zur {{ meeting.type }} am {{ meeting.date | date: "%d.%m.%Y" }} in {{ meeting.location }}]({{ meeting.url }}){% endfor %}
{: class="liste"}
