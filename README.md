# CarWash

## Use Case Diagram
![UseCaseDiagram](https://github.com/aKentorp/CarWash/blob/master/UseCaseDiagram2.png)

### Buy Wash card Use case and SSD
Buy WashCard:

Primary actor: Customer

Main Success scenario: 
Customer requests to buy a washCard. The system ask the customer to enter the initial value of the washCard (200- 1000 kr.). The customer chooses the initial amount and pays.
The system creates a user with the customer ID and credit. The customer receives the washCard.

Alternative flow:
If the customer doesn’t buy a washCard with a value between 200 - 1000, the system decline the customers request to buy a card and returns to the menu.
If the system is down or shows an error message, the customer will ask a staff member for help. The staff member reboots the system.
If the system is still unresponsive, the staff member calls maintenance.

![BuyCardSSD](https://github.com/aKentorp/CarWash/blob/master/buyWashCard%20SSD.jpg)

### Recharge Card Use case and SSD

Primary actor: Customer

Main success scenario:
Customer requests to deposit money into their account. The system request a wash card. Customer insert wash card. The system asks for an amount. Customer enters an amount to be deposited into their account and deposits money. The system updates account and verifie with a message or reciept.

Alternative flow:
Customer tries to deposit an amount there is not between 0 -1000. System gives an error message and asks customer for the correct amount of money. Customer selects an option and continues from that step.

![RechargeCardSSD](https://github.com/aKentorp/CarWash/blob/master/Recharge%20SSD.jpg)

### Wash car Use case and SSD

Primary actor: Customer

Main Success scenario: 
The customer request to wash their car. The System ask the customer for their wash card.The customer insert the wash card. the System ask the customer which car wash they would like, from a list. The customer enters the desired wash. The system charges the account according to the wash price. The system starts and completes the Car Wash. The system shows a message, when the wash has completed. After the wash is completed, the system automatically update the wash statistics.


Alternative flow:
The customer has insufficient funds on their account. the system asks them to recharge their card, choose a different wash, or to cancel the purchase.
Car wash has an error or shuts down before completion. The system asks the customer to contact staff. Staff reimburses the customer manually and restarts the system.

![WashCarSSD](https://github.com/aKentorp/CarWash/blob/master/Wash%20Car%20SSD.jpg)

### Check balance Use case and SSD

Primary actor: customer

Main success scenario:
Customer asks system to check their balance.System request wash card. Customer inserts wash card. System checks balance of the card. The system shows the customer their balance on the screen.

Alternative flows: 
Customer doesn’t have their wash card. Customer asks staff to manually check their account balance.

![CheckBalanceSSD](https://github.com/aKentorp/CarWash/blob/master/CheckBalance%20SSD.jpg)

### Check statistics Use Case

Primary actor: Owner

Main Success scenario: 
The owner open the statistics file.


Alternative flows:
The file is missing, the owner contact support. 
If the owner would like additionally statistics. The owner contacts support.


## Domain Model
![Alt Text](https://github.com/aKentorp/CarWash/blob/master/Domain%20model%20.jpg)

## Class diagram
![ClassDiagram](https://github.com/aKentorp/CarWash/blob/master/CarWash.jpg)

## Business model Canvas
![Canvas](https://github.com/aKentorp/CarWash/blob/master/Canvas.png)

## Furps+ - Car Wash

### F - unctionality
* Capability
* Nescessary car wash functionality
* statistics
* Reusability
* could be used by just about any car wash company
* Security
* Very replicable :(

### U - sability
* Human factors
* Very consumer friendly
* Aesthetics
* Bare bones
* Consistency
* Should work every time
* Documentation
* Gives statistical feedback to car wash owner
* Responsiveness
* Shouldn’t have any problems

### R - eliability
* Availability
* low failure frequency
* Failure, extend and time length
* Instantanious recoverability
* Predictability
* Stable
* Accuracy
* low severity of errors

###  P - erformance
* Speed
* instantanious
* Efficiency
* Highly efficient
* Resource consumption
* low
* Throughput
* high
* Capacity
* high
* Scalability
* Insanely scalable


###  S - upportability
* Testability
* Shouldn’t require little to no service
* Flexability
* Can be modified with some work
* Installability
* Can’t be installed so far
* Localizability

## Risk analysis

![RiskAnalysis](https://github.com/aKentorp/CarWash/blob/master/RiskAnalysis.jpg)

