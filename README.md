# Cryptocoin
Analyze the Cryptocoins class and its member variables:
The Cryptocoins class has two member variables, prices_ and supplies_. Prices_ is an unordered_map that stores the prices of coins by their names, and supplies_ is an unordered_map that stores the supplies of coins by their names. These two maps will be used to keep track of the prices and supplies of the coins in the portfolio.

Implement the Cryptocoins constructor:
The constructor for the Cryptocoins class should initialize the prices_ and supplies_ member variables to empty maps. You can do this by using the default constructor for the unordered_map class.

Implement the addCoin() function:
The addCoin() function should take three parameters: the name of the coin, the price of the coin, and the supply of the coin. It should add the coin to the portfolio by inserting the name, price, and supply into the prices_ and supplies_ maps. If the coin already exists in the portfolio, the function should return false, indicating that the coin was not added. If the coin was successfully added, the function should return true.

Implement the removeCoin() function:
The removeCoin() function should take one parameter: the name of the coin. It should remove the coin from the portfolio by erasing the name, price, and supply from the prices_ and supplies_ maps. If the coin does not exist in the portfolio, the function should return false, indicating that the coin was not removed. If the coin was successfully removed, the function should return true.

Implement the buyCoins() function:
The buyCoins() function should take three parameters: the name of the coin, the amount of coins to buy, and a reference to a double variable that will hold the total price of the coins. It should check if the coin exists in the portfolio and if there is enough supply to buy the requested amount of coins. If both conditions are met, the function should update the supply of the coin and calculate the total price of the coins. It should then return true, indicating that the purchase was successful. If the coin does not exist in the portfolio or there is not enough supply, the function should return false, indicating that the purchase was not successful.

Implement the sellCoins() function:
The sellCoins() function should take three parameters: the name of the coin, the amount of coins to sell, and a reference to a double variable that will hold the total revenue of the coins. It should check if the coin exists in the portfolio and if there is enough supply to sell the requested amount of coins. If both conditions are met, the function should update the supply of the coin and calculate the total revenue of the coins. It should then return true, indicating that the sale was successful.
