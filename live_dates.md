---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: about
title: LIVE DATES
---

<h2>LIVE DATES</h2>



{% assign current_date = site.time | date: "%Y-%m-%d" %}
{% if current_date < site.southendjazzfest_date %}
Amalgam are playing at the [Southend Jazz Festival](https://www.southendjazzfestival.com/what-s-on)!

Friday 4th October 2024 - Southend-on-Sea - Twenty One bar [Click here to buy tickets](https://www.ticketsource.co.uk/southendjazzfestival/amalgam/2024-10-04/20:00/t-krezmzp)
{% else %}
  <p>No confirmed live dates at present.</p>
{% endif %}