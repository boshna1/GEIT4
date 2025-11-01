Game Engines Lab 3

Joshua Dinata
100921955

Make Food!
Core loop is to make food for customers with 4 types of ingredients, but only 2 types of dishes. Burger and Hotdog

Flowchart: https://www.canva.com/design/DAG3eSvDHZs/LcoVWdnwGK5_7SoZYiZXtQ/edit?utm_content=DAG3eSvDHZs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

The element of my game that adopts the Observer pattern are the AI_Customer and BP_Board. The BP_Board acts as the sender, notifying customers when food is prepared and also if it is correct. In this case if it is a burger or a hotdog. The AI_Customer is notified through an inherited function from BPI_Observer, event Notify. Moving the customer to the counter, taking the food and returning.

This pattern is good because a type of dish made can notify certain customers and more than one, in my case I just have all of them recieve the produced food. It can be modular with more ingredients, amount and type of customer, just need to subscribe customer to board to notify when food is done.
