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

# Where can I stay?
We're looking at different AirBnB options right now, but otherwise Exeter has a number of hotels or BnBs that should work.
Exeter's not a huge place, so anything close enough to the train stations (Central, St Davids, St Thomas) will be pretty walkable to all our wedding stop-offs.

# Do I have to get you something?
No, but if you feel you *absolutely have to* get us something, we're putting together a list to make this easier for people.
The list so far is available through this link:  
[https://www.johnlewis.com/wish-list/TTTNFVK](https://www.johnlewis.com/wish-list/TTTNFVK)  
If you pick something from the list, we'll remove it!

Other vendors we like if you want to shop small (in Exeter):
- Maker Maker, Magdalen Road
- Helen of Troy, Fore Street
- Maker Mart, Gandy Street
- Smith's Wines, Magdalen Road
- Tappermade, [Magical internet land](https://tappermade.com/)
- Crankhouse Coffee, Fore Street
- Or go rogue and stray from the list, we also like surprises!

If you want to buy us coffee stuff, we already have a lot of equipment, please check with us first (Mia wants another set of espresso cups).

# What should I wear?
The ceremony is on grass so avoid skinny heels. Don't feel obliged to wear a three-piece suit if it's 30 degrees, we want everybody to be comfortable. Think beach-formal!

# Should I eat lunch?
Yes! Please eat beforehand, we recommend a small lunch or big brunch as food servicee will be an early dinner!

# Wedding updates:
Here's a list of our previous updates on the wedding.
{% for post in site.categories.wedding %}
<a href="{{ post.url | remove_first:'/'}}">{{ post.title }}</a> 
{% endfor %}
