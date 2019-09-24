# M2M
### Machine to Machine communication protocol

With ever-increasing interactions between humans and machines, standardizing the communication between the two can make more efficient use of and streamline the interactions. In the business world, machines play an important role as a middle man (i.e. buying tickets, online shopping, booking a dentist appointment online) and every system has a different set of rules and requirements while in the abstract, every interaction is very similar. 

Let's compare booking flights and buying a pizza online. Both need a price, extra charges( baggage charges in the flight and toppings on the pizza), date and time (time for the flight, time for the delivery or picking up the pizza), location (flying from/to flight, restaurant location and delivery address for pizza) and reviews (reviewing applies to both). This is just one of many cases where the formula of interaction is exactly the same with just different parameters.

* M2M aims to extract the underline layer from the interaction; separating the core logic and the parameters. *

---
### There are two parts of M2M implementation: the core logic and parameter wrapping.

1. The core logic(HOW) is the request made (ordering a pizza or booking a flight) and handling the response (pizza shop closed or flights sold out)

2. Parameter wrapping(WHAT) is formatting the parameters (price, time, location, etc...) so that the core logic can interpret it. 

---

### Realife applications.

* Voice assisted appointment booking
* Using sound and images to interact with machine and humans
* Automated trades for commercial consumers 
* Using Siri/Alex/GA for ordering pizza
* Leaving online reviews with voice or picture
* Schedule task (i.e. a calendar event) to execute

---
