# Zoopla House Search

I've been living in London for over 5 years now and every time I need to move out it's the same struggle: how to find the best place in the market, well located and still pay less for it.
Some people purely go for aesthetics and are bound to close the deal that blows their budget. Others like me end up spending too much time looking in different websites, going to viewings and still not shake hands because comfort and budget were not met.
It was in my struggle that I decided then to automate my search. I saw some components of my search: data gathering, data ranking and closing a deal.
If you are looking for an automated way to improve your house search, you've come to the right place. Now seat back and let the machine do the hard work for you.

# Nifi Flow parameters

To start the flow, some changes need to be made:
apiKey: Zoopla Developer API Key
maximumBeds: Maximum number of beds the user is interested in
maximumPrice: Maximum price (per week) the user is interested in
minimumPrice: Minimum price (per week) the user is interested in
pageSize: Internal parameter for size of pages. Should be 100.
postcode: Postcode of interest for the search
radius: Radius, in kilometers, of houses to be considered from the postcode especified

# Work in progress

Save an image on hub.docker.com with all required softwares pre-installed so it's easier for people to reproduce what's been achieved.

