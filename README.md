To use open in Google Chrome.

My goal here is to learn how to use D3.js with svg, and
and in doing so create an interactive map of the United States to display voting history data from the past three elections.

Because of irregularities in the voting data, as well as the presence of many extremely small parties. I grouped the voter data into three variables; Democratic, Republican and Other.

I read through several tutorials on D3 and using D3 with interactive maps, I found the most useful guides to be in the D3 documentation, where they had several examples of interactive maps. D3 is a deep well, there is so much in this library to use. I used Codepen.io for a lot of the trial and error development.

A difficulty I had was changing the map dynamically based on user input, specifically the selecting of a specific year. After a lot of JSON massaging, I found that I misunderstood how D3 interacts with svg, as it pertains to updating an image. Once I knew how they interacted, I was able to construct methods, specifically method callbacks, that allowed for an updated image.

As to the fake submission, I assumed that the intent was to temporarily display user data, but not to permanently change it. This allowed me to continue calling data externally.

The svg data of the map, which is from the D3 documentation, can be found locally, and the election data is all called externally. Once I get an acceptable working draft, I will start moving this to REACT.js
