Download Link: https://assignmentchef.com/product/solved-cs3431-homework-1
<br>
<strong><u>Problem 1 (Car-Race Database)</u></strong>

Design an Entity-Relationship Diagram (ERD) for a <strong><u>car race database</u></strong> with the following requirements.

<ul>

 <li>We have cars, for each car we keep its VIN number (unique ID), engine type, color, make, and model</li>

 <li>We have drivers, for each driver we keep ID (unique), name, DoB, and age (derived attribute)</li>

 <li>Drivers use cars to enter races, each race has some attributes such as the race number (unique ID), race type, the number of rounds, and date.</li>

 <li>Each driver can enter many races and can use the same car or a different one in each race. Thus, the same car can participate in many races.</li>

 <li>In the design, we want to capture which car is used by which driver and in which race.</li>

 <li>We also need to capture the winner of each race (the driver who won the race) and the winning time (the time taken to finish and win the race).</li>

 <li>Cars may get into accidents. We need to capture the accident history of cars. For each accident, we need to capture the involved car(s), involved driver(s), and the race in which the accident took place.</li>

</ul>




<strong><u>Problem 2 (Mini-Store Database) </u></strong>

Design an ER diagram for a <strong><em><u>mini store</u> </em></strong>that represents the following requirements.

<ul>

 <li>We have items, each item has a unique ItemID, price, type, and name.</li>

 <li>We have customers, each customer has unique CustID, name, and address.</li>

 <li>Each customer can make many transactions, in each transaction a customer may buy one or more items and for each item there is a quantity, e.g., customer 1 makes a transaction buying 3 milk bottles, and 2 canned meat, and 1 chocolate.</li>

 <li>We also need to capture the transaction date and the total price.</li>

 <li>Customers may return items that they have previously bought, e.g., customer 1 may return 2 milk bottles from the 3 ones he previously bought. In this return transaction, we need to keep track of which item has been returned, the quantity, the return time, and the original buying transaction.</li>

</ul>







<ul>

 <li><em>Note: Try to have good design that does not have redundant (un-needed) relationships. Redundancy will be penalized.</em></li>

</ul>








