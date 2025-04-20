# super.com case study

Super.com is an online travel agency (OTA) that sells hotel rooms to consumers through our automated chat-bot, accessible through Facebook Messenger, SMS, Whatsapp and other platforms. We aim to improve the hotel-booking experience by making it mobile-friendly and as easy as chatting with a friend. Some of the ways that we advertise our hotel rooms is through common hotel booking sites that aggregate rates from many OTA’s. We are able to determine how much we’d like to spend on each click. We can set a different spend per click for each itinerary (itinerary is the unique inputs of the search: hotel / length of stay / checkin date / etc...). If we spend more, we will be more likely to be shown and will appear higher in the ranking. If we spend less, we will be shown lower in the ranking but if our bid is too low, we may not be shown at all.

Spend Data:
- Spend data is provided to us by an external partner. Their definition is that each row
represents a unique itinerary as defined by (date, hotel_id, dta, los, and booking_dow). All other fields are metrics at that grain. This does not guarantee that they've passed the data accurately.

Bookings Data:
- Bookings Data is logged by an internal system and passed to us directly from the logging database. The records are listed by the date that the record was created, however the data gets appended together with the bookings from the last hour of data.

**Question 1**
Please reflect on the following questions. Please use any combination of graphs/prose to explain your answers:
- What types of itineraries are popular? Within our popular itineraries, what key trends are you seeing?
- What changes would you recommend to increase Super.com’s success?
- What’s an interesting insight from the data that you’d like to dive deeper on?
  
**Question 2**
You are tasked with a new project to launch Super.com in new countries (assume we are only operating in the USA as of now).
- How would you approach this problem?
- Who would you involve?
- Where would you launch first?
  
Please also list out the data aggregations (dimensions, metrics) with descriptions into how you would incorporate it into your decision making process.


 

