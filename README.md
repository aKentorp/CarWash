# CarWash

## Use Case Diagram
https://github.com/aKentorp/CarWash/blob/master/CarWash%20Use%20Case%20Diagram.pdf

### Buy Wash Card Use Case
Buy WashCard:

Primary actor: Customer

Main Success scenario: 
Customer requests to buy a washCard. The system ask the customer to enter the initial value of the washCard (200- 1000 kr.). The customer chooses the initial amount and pays.
The system creates a user with the customer ID and credit. The customer receives the washCard.

Alternative flow:
If the customer doesn’t buy a washCard with a value between 200 - 1000, the system decline the customers request to buy a card and returns to the menu.
If the system is down or shows an error message, the customer will ask a staff member for help. The staff member reboots the system.
If the system is still unresponsive, the staff member calls maintenance.


## Domain Model
![Alt Text](https://github.com/aKentorp/CarWash/blob/master/Domain%20model%20.jpg)


