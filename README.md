# portico-producer-consumer
This is a project for college that addresses such issues: 
* the HLA architecture,
* FOM modeling,
* federate synchronization.
  
All these elements are included in the implementation of such a situation:

The restaurant has a certain number of tables. Customers show up every random time.
Incoming customers queue up. They get in when there is a free table, otherwise they stay
in line or leave (random customers are impatient). Once a table has been occupied for
a random amount of time, the waiter processes the order. After the first meal, a second meal
is ordered with some probability. After that, the customer pays and leaves the restaurant.
 Estimate the average waiting time for a table.
