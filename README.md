# goit-js-hw-02

# JavaScript Fundamentals: Logic and Conditional Statements

This section focuses on control flow, string manipulation, and the `switch` statement in JavaScript.

---

## Task 1: Order Logic (Conditionals)
**File:** `task-1.js`

Enhance the droid sales function to check for sufficient funds before completing a transaction.
- **Parameters:** `quantity` (number), `pricePerDroid` (number), `customerCredits` (number).
- **Logic:**
  - Calculate `totalPrice`.
  - If `totalPrice` exceeds `customerCredits`, return `"Insufficient funds!"`.
  - Otherwise, return success message with order details.

---

## Task 2: Message Formatting (Slicing)
**File:** `task-2.js`

Create a function `formatMessage(message, maxLength)` that truncates long strings to prevent layout overflow.
- **Logic:**
  - If the string length is within `maxLength`, return it as is.
  - If it exceeds `maxLength`, cut the string to the limit and append an ellipsis (`...`).

---

## Task 3: Spam Detection (String Normalization)
**File:** `task-3.js`

Implement a function `checkForSpam(message)` to identify prohibited keywords regardless of their case (e.g., "SPAM", "sAlE").
- **Logic:**
  - Convert the entire string to lowercase.
  - Check for the presence of keywords: `spam` or `sale`.
  - **Returns:** `true` if found, `false` otherwise.

---

## Task 4: Shipping Cost (Switch Statement)
**File:** `task-4.js`

Develop a function `getShippingCost(country)` that calculates delivery fees using a `switch` statement for specific regions.
- **Supported Regions:**
  - China: 100 credits
  - Chile: 250 credits
  - Australia: 170 credits
  - Jamaica: 120 credits
- **Logic:** Returns a specific cost message or a "No delivery" error if the country is not in the list.