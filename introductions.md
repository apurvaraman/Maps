---
layout: post
author: Apurva Raman
title: introductions
---
# map

here is my [first map](https://apurvaraman.github.io/maps/first-map)

# on a first foray into web maps:

Looking into tiled maps was really interesting, especially since I set out to make my map with something that wasn't Web Mercator. Specifically, I set out to make a fun Waterman Butterfly map. As you might have noticed, the map above is most definitely not a Waterman Butterfly graph. It's still Web Mercator. So what happened?

A little poking around for how to do different projections led me to [proj4](https://proj4.org/), which plays well with leaflet, apparently. Once I worked through the example, I saw that they were drawing from a set of projections that included useful things like local projections. That set did not include Waterman Butterfly, at least as far as I could find. Moreover, even if I set the coordinate system correctly, I still needed tiles in that projections. The way to do this seems to be to make your own tiles/tileserver with mapnik or some such. This seemed like a bit much, especially since I wasn't sure that I could easily get a Waterman Butterfly out of it, and thus I let the map be. I'm somewhat baffled that there's not just a bunch of servers with all sorts of selection of tiles.

# on Exactitude in Science:

I was debating whether to bring this up last class when we were talking about the uselessness of perfect representations of the world, but I couldn't remember the name of the story. I read a fair bit of Borges in junior year of high school, but didn't come across this particular story until my semester at RISD in my spatial dynamics class. The imagery of deliverance of the perfect/useless map to nature and nature's consumption/integration of that model stuck with me, as well as the sense of ever-growing maps/ever-refined models. I don't really think I thought about this story in the context of maps, but whenever discussions come up about extremely detailed data collection for constructing extremely detailed models, I can't help but be reminded of this useless map. I think it's also notable that this scientific pursuit is a pursuit of Empire: that the act of spreading a map over the land, point for point, and labeling and defining a correct, exact state is a conquering and colonizing act.

# on Procession of Simulacra:

Here's something new! I had some unformed thoughts about imperialism and this kind of thing which I feel is pretty accurately described as simulation. It seems to me that thinking about models made from data as simulation is a useful framing, rather than an incomplete one. At first as I was a bit skeptical- a lot of data collection is not about simulation, right? Is my heart rate data a simulation? It felt kind of strange at first, but if I think about the data being used for a model, to test an assumption, as a thing to draw conclusions from, it becomes clear that it is a sort of simulation. Given that we venerate this data with a level of sanctity that comes from its place as scientific and therefore infallible, it makes sense that it takes precedence over actual observable nuanced truth. That image of the Earth rotting away beneath the Map! Those who make and control the maps that we all use as a proxy for the real hold so much power.

# on Experimental Geography

Before reading this, I had no real sense for what the discipline of geography was, is, or could be. The idea of a discipline driven by the application of axioms to any given situation where it applies is intriguing, certainly. Defining a methodology (quite loosely, not even a process, like design can be) and using that rather than a subject to carve out a discipline is not something I think I fully grasp the implications of. The notion that geography is necessarily more than critical and explores experimental construction of alternatives is really appealing. I think I can see how some of this might work, but I'm still a bit skeptical.
