# SeniorProject
This project offers an innovative approach aimed at optimizing the warehouse operations of Totomak company. Totomak company is moving from its old warehouse to a new warehouse and is facing warehouse layout and efficiency issues due to the random product placement practice available in the new warehouse. This means that the products in the warehouse are randomly placed on the shelves. However, when a product needs to be placed on the shelf, the forklift moves from the starting point, randomly places the product on an empty shelf, and then returns to the starting point. Similarly, when there is a product to be sent for shipment, the forklift moves from the starting point, searches for the location where the product is located, picks up the product and returns again. 

In order to solve these problems, it is aimed to create a decision support system in order to increase the efficiency of the warehouse operations of the Totomak company.  For this reason, the decision support system makes a shelf allocation for the products to be used within this period, based on the demand list of the Totomak company for the specified time period. These reservations allow the products to be determined in advance and to prevent them from being placed randomly. However, it is aimed to determine which shelves the products will be placed on and to minimize forklift movements according to the determined shelf arrangement. At the same time, the items to be placed on and off the shelf are paired to minimize the distance the forklift travels. This approach is of great importance in terms of optimizing forklift movements and saving energy.

In addition, the selection of the products to be placed on the warehouse shelves and to be shipped in line with the FIFO policy is also provided within the scope of the project. This policy facilitates the consumption of products in the correct order and the management of warehouse stocks. Thus, a chaotic order in the warehouse will be avoided, FIFO policy will be adopted and warehouse operations will be carried out more regularly.

First Pyhton code is created for solving the shelf allocation part as an assignment problem, which is named main.py. On the other hand, Model2.py is created for minimize the forklift movement. Finally excel userface is created for these codes, it allows the user to perform the desired operations directly on excel without getting confused. Python connection is made with Excel interface.
