---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: about
title: Get info about our wedding here!
---

![Save-The-Date image](/assets/img/savethedate.jpg)

# When
**Sun 18th August 2024**

# Where
Exeter Plan:
<iframe src="https://www.google.com/maps/d/embed?mid=1jl8mwE_gY4SU3c9C_t0Cq4HsQ38iAno&ehbc=2E312F&noprof=1" width="640" height="480"></iframe>
- Wedding ceremony - Exeter Larkbeare House 2:30pm
- Dinner - Stage Restaurant Madgdalen Road 4(ish)pm
- After party - Topsham brewery (after dinner)
- <a href="https://www.google.com/maps/d/edit?mid=1jl8mwE_gY4SU3c9C_t0Cq4HsQ38iAno&usp=sharing" target="_blank">Google maps of locations</a>

Malaysia plan:
- TBD

# Can I come?
Of course! If you can find this website, you can come.
I (Brandon) am extremely bad at getting things out to people, and keeping on top of things like messages, so invites may (read *will*) be pretty slow to come out!
If you'd like to come, please do, we'd love to have you here with us!

# Where can I stay?
We're looking at different AirBnB options right now, but otherwise Exeter has a number of hotels or BnBs that should work.
Exeter's not a huge place, so anything close enough to the train stations (Central, St Davids, St Thomas) will be pretty walkable to all our wedding stop-offs.

# Do I have to get you something?
No, but if you feel you *absolutely have to* get us something, we're putting together a list to make this easier for people.
The list so far (If you message us that you're getting it, we'll strike it through):
- Wine glasses

# Wedding updates:
Here's a list of our previous updates on the wedding.
{% for post in site.categories.wedding %}
<a href="{{ post.url | remove_first:'/'}}">{{ post.title }}</a> 
{% endfor %}
