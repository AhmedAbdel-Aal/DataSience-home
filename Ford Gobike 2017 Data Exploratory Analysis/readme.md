# Ford Gobike 2017 Data Exploratory Analysis

## Data-set

The data-set is mainly about information about the rides that has been done by individual rides in a bike-sharing system. This system depends on the presence of user types [customers, subscribers].
The data-set is provided yearly.
The data-set is providing the start and end (stations names and ids, date and time, sations locations, duration of the ride).

## Summary of Findings

In the exploration, I found that that data-set is mainly splitted by ratio of 3:1 to two groups,
subscriber and customers respectively. However, the mean od the ride duration for customers is higher than the corresponding mean of the ride duration for subscribers.

By inspecting the number and duration of rides made be each group, I found that
each group has some interesting properties which can be used to address new and
suitable offers by the company to attract more users and make the best use of the
current subscribers and customer.

For the ride duration of customers:
- 75% of the customers take the ride for more than 10 mins.
- 50% of the customers spend between 10 min and 30 mins.
- 25% of the customers last for more than 30 mins.
- The number of rides made by customers in holidays (sundays, saturdays)are higher than the other days of the week.

While, for subscribers:

-  The amount of rides made the subscriber are the highest at 8 AM and 5PM in the working days. this interesting fact can warn us to be sure of covering the the number of subscribers we have with corresponding number of rides, and target more people going to work and not subscribed yet.

## Key Insights for Presentation

For the presentation, I focused on the properties of the two user types i.e., customers and subscribers.
Each group showed some facts that could be used by the bike company to target more
users and offer the most suitable offers for the current users.

Firstly, a comparison between each group ride numbers are done, then I inspected the
duration of rides made on a group level. Secondly, the starting hour of each ride for each day 
in the week for subscribers are inspected by a count plot with a different color for each day, 
which showed how the behaviour of the subscribers through out the week. Lastly, the number
of rides each day showed that customers are more active on holidays than the other days.
The subscribers also active, but not as the other days.