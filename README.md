
# goit-js-hw-02
This repository contains three JavaScript functions solving different tasks.

## `task-1.js` - `makeTransaction(quantity, pricePerDroid)`

Calculates the total cost of purchasing droids and checks if the customer has enough credits to make the transaction. 

**Params:**
-  `quantity` (number) – number of droids
-  `pricePerDroid` (number) – cost per droid
-  `customerCredits` (number) – available credits for the customer  

**Example:**
```js
makeTransaction(3, 1000, 15000)); // "You ordered 3 droids worth 3000 credits!"
makeTransaction(10, 5000, 8000)); // "Insufficient funds!"
```
 
---
## `task-2.js` - `formatMessage(message, maxLength)`

Formats a message by truncating it to the specified length and appending '...' if the message exceeds the `maxLength`.

**Params:**
-   `message` (string) – the original message
-   `maxLength` (number) – maximum allowed length for the message

**Example:**
```js
formatMessage('Curabitur ligula sapien', 16); // "Curabitur ligula..."
```

---
## `task-3.js` - `checkForSpam(message)`

Checks if the message contains the words 'sale' or 'spam' (case insensitive).

**Params:**
- `message` (string) – the message to be checked

**Example:**
```js
checkForSpam('Latest technology news'); // false
```
---
## `task-4.js` - `getShippingCost(country)`

Calculates the shipping cost based on the destination country.  
If the country is not supported for delivery, it will return a message indicating that delivery is unavailable.  

**Params:**  
- `country` (string) – destination country  

**Example:**  
```js
getShippingCost('Australia'); // "Shipping to Australia will cost 170 credits"
```
