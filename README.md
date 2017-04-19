My goal here is to learn how to use D3.js with svg, and to
and in doing so create an interactive map of the United States to display voting history data from the past three elections.

I read through several tutorials on D3 and using D3 with interactive maps, I found the most useful guide to be in the D3 documentation, where they had several examples of interactive maps.

A difficulty I had was changing the map dynamically based on user input, specifically the selecting of a specific year. After a lot of JSON massaging, I found that I misunderstood how D3 interacts with svg, as it pertains to updating an image. Once I knew how they interacted, I was able to construct methods, specifically method callbacks, that allowed for an updated image

The svg data of the map can be found locally, and the election data is all called externally. I used the map data from the D3 documentation.
