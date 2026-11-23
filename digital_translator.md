PY-SECTION 1 MISSION PROJECT
THE DIGITAL TRANSLATOR

Name: Owoicho Enenche
Course: Python Programming
Section: 1 – The Digital Translator

TIER 1 — BASIC UNDERSTANDING: THE LITERAL ASSISTANT
The Challenge: Make Me Breakfast

If I tell someone to make me breakfast, they might understand what I mean without needing many details. However, a computer cannot work that way because it needs clear instructions to know exactly what to do.

To make the instruction understandable to a computer, I would break it down into smaller steps.

My Instructions
Go to the kitchen.
Locate two eggs, two slices of bread, butter, salt, and cooking oil.
Collect a frying pan, a spatula, a plate, and a cooking spoon.
Place the frying pan on the stove.
Turn on the stove and add a small amount of cooking oil to the pan.
Crack the two eggs into a clean bowl.
Add a small amount of salt and beat the eggs with a fork.
Pour the beaten eggs into the heated frying pan.
Allow the eggs to cook, then carefully turn them with the spatula.
Remove the eggs from the pan once they are fully cooked.
Place the two slices of bread on a plate.
Spread a little butter on each slice.
Place the cooked eggs beside the bread.
Turn off the stove.
Place the finished breakfast on the dining table.
Reasoning Challenge

Which parts of my original instruction required me to make assumptions?

The original instruction, "Make me breakfast," leaves out a lot of important information.

For example, it does not explain what type of breakfast I want, how many eggs should be prepared, what ingredients are available, or what equipment should be used.

It also does not explain how the food should be prepared or where the finished breakfast should be placed.

A human might make reasonable decisions based on experience, but a computer needs those details to be provided through instructions.

This shows why instructions need to be clear, specific, and properly arranged.

TIER 2 — FIELD EXERCISE: ALGORITHM THINKING
The ATM: Withdrawing Money

An ATM withdrawal is something people do regularly, but there are several processes that must happen before money can be successfully withdrawn.

An algorithm helps organize these processes into a logical sequence.

My ATM Withdrawal Algorithm
Approach the ATM.
Insert the bank card into the card reader.
The ATM checks whether the card can be read.
If the card cannot be read, display an error message and ask the customer to try again or use another card.
If the card is accepted, request the customer's PIN.
The customer enters their PIN.
The ATM checks whether the PIN is correct.
If the PIN is incorrect, display an error message and allow another attempt, within the bank's permitted limit.
If the PIN is correct, display the available banking options.
Select the withdrawal option.
Enter the amount of money to withdraw.
The ATM checks whether the account has enough money.
If the balance is insufficient, display a message explaining that there are not enough funds.
If the balance is sufficient, check whether the ATM has enough cash available.
If the ATM does not have enough cash, inform the customer and allow them to enter a different amount or cancel the transaction.
If everything is correct, authorize the transaction.
Dispense the requested cash.
Update the customer's account balance.
Display a transaction confirmation.
Return the customer's card.
End the transaction.
Handling Possible Problems

1. What happens if the card cannot be read?

The ATM should display an error message explaining that the card could not be read. The customer can try inserting it again or use another card.

2. What happens if the PIN is incorrect?

The ATM should inform the customer that the PIN is incorrect and allow another attempt. If the maximum number of attempts is reached, the transaction should stop and the card may be retained or blocked according to the bank's security rules.

3. What happens if the requested amount is greater than the available balance?

The ATM should reject the withdrawal and inform the customer that the account does not have enough money. The customer can enter a smaller amount.

4. What happens if the ATM does not have enough cash?

The ATM should display a message explaining that it cannot dispense the requested amount. The customer can choose another amount or cancel the transaction.

5. What happens if the transaction cannot be completed?

The ATM should stop the transaction safely, display an appropriate error message, and avoid deducting money without successfully completing the withdrawal. If money has already been deducted, the system should have a process for reversing or investigating the transaction.

My Understanding

The main difference between a problem and an algorithm is that a problem describes what we want to achieve, while an algorithm explains the steps needed to achieve it.

For example, withdrawing money is the problem, but inserting a card, verifying a PIN, checking the balance, and dispensing cash are parts of the algorithm.

A program is what turns those instructions into something a computer can execute.

The relationship is:

Problem → Algorithm → Program

TIER 3 — PRACTICAL EXERCISE: INPUT → PROCESSING → OUTPUT
The Simple Calculator

A calculator is a good example of how a computer receives information, processes it, and produces a result.

For this exercise, we have two numbers:

python
number_1 = 20
number_2 = 5


The calculator will perform four mathematical operations using these numbers.

1. Addition
Input: 20 and 5.
Processing: Add the two numbers together.
Output: 25.

Calculation:

text
20 + 5 = 25

2. Subtraction
Input: 20 and 5.
Processing: Subtract the second number from the first.
Output: 15.

Calculation:

text
20 - 5 = 15

3. Multiplication
Input: 20 and 5.
Processing: Multiply the two numbers.
Output: 100.

Calculation:

text
20 × 5 = 100

4. Division
Input: 20 and 5.
Processing: Divide the first number by the second.
Output: 4.

Calculation:

text
20 ÷ 5 = 4

Summary Table
Operation	Input	Processing	Output
Addition	20, 5	20 + 5	25
Subtraction	20, 5	20 - 5	15
Multiplication	20, 5	20 × 5	100
Division	20, 5	20 ÷ 5	4
Reasoning Challenge: Division by Zero

What happens if the second number is zero?

For example:

python
number_1 = 20
number_2 = 0


If the calculator tries to divide 20 by 0, it encounters an error because division by zero is mathematically undefined.

A properly designed program should check the second number before performing division.

If the number is zero, the program should display a message explaining that division by zero is not allowed instead of attempting the calculation.

My Understanding

This exercise shows that a computer program follows a process to produce a result.

It receives information through input, performs an operation through processing, and provides the result through output.

The three stages are connected:

INPUT → PROCESSING → OUTPUT

Without input, the program has no values to work with. Without processing, nothing happens to the information. Without output, the user cannot see the result.

TIER 4 — CONCEPTUAL CHALLENGE: DATA TRANSLATOR
Understanding Customer Information

A computer needs information to be represented in a way that it can store and process.

Consider the following customer information:

Customer name: Victor
Age: 30
Account balance: 150000.50
Account active: Yes
Identifying the Data Types
Information	Value	Data Type
Customer name	Victor	String (Text)
Age	30	Integer
Account balance	150000.50	Float (Decimal number)
Account active	Yes	Boolean
Why Each Data Type Matters

1. Customer Name – String

The name Victor is text, so it is represented as a string. A computer needs to recognize it as text rather than treating it as a mathematical value.

2. Age – Integer

The age is represented as an integer because it is a whole number without a decimal point.

3. Account Balance – Float

The account balance contains a decimal value, so it can be represented using a floating-point number in a basic programming example.

For real financial applications, decimal arithmetic is generally preferred to avoid floating-point rounding issues.

4. Account Active – Boolean

The account status represents a condition that can either be true or false.

For example:

True means the account is active.
False means the account is inactive.
How Is This Information Represented Digitally?

Computers ultimately work with binary data, which consists of two digits: 0 and 1.

Text, numbers, and Boolean values are represented using different encoding and storage methods.

For example, the name Victor must be converted into character codes that the computer can store. Numerical values also have their own representations.

The general process is:

Real-World Information → Data Representation → Digital Representation → Binary Data → Computer Storage

Reasoning Challenge

What could happen if the account balance is stored incorrectly?

If the account balance is stored incorrectly, it could cause serious problems for the customer and the bank.

For example, if a customer's actual balance is 150000.50 but the system mistakenly interprets it as 15000.50, the customer might appear to have less money than they actually do.

This could affect withdrawals, payments, transfers, and account statements.

It shows that storing information correctly is important because computer systems depend on accurate data to produce correct results.

My Understanding

Data representation helps computers distinguish between different types of information.

A name, an age, an account balance, and an account status do not all mean the same thing. They need to be represented appropriately so that a program can process them correctly.

This is why data types are important in programming.

TIER 5 — ARCHITECTURE CHALLENGE: EXPLAIN THE WHOLE SYSTEM
The Online Store

An online store is a good example of how different parts of a computer system work together.

When a customer orders a product, several things happen before the order is confirmed.

1. Customer Input

The process begins when a customer visits an online store and selects a product.

The customer provides information such as:

The product they want to purchase.
The quantity they want.
Their name and contact information.
Their delivery address.
Their payment information.

This information is the input that enters the system.

2. Application / Program

The online store application receives the customer's information.

The application contains instructions that tell the computer how to handle the order.

For example, it knows how to display products, accept customer information, calculate prices, and process orders.

3. Instructions

The program follows a series of instructions to complete the customer's order.

These instructions might include:

Identify the selected product.
Check whether the product is available.
Confirm the requested quantity.
Calculate the total cost.
Validate the customer's information.
Process the payment through a payment service.
Save the order details.

Each instruction tells the computer what action to perform.

4. Data Processing

After receiving the customer's information, the computer processes it.

For example:

text
Product price: 50,000
Quantity: 2

Total = 50,000 × 2

Order total: 100,000


The program uses the product price and quantity to calculate the total amount the customer needs to pay.

It also checks other information to make sure the order can be completed.

5. Stored Data

Once the order has been processed, important information needs to be stored.

This allows the online store to remember the transaction and retrieve it later.

The information might include:

Customer details.
Product name or ID.
Quantity ordered.
Total amount paid.
Delivery address.
Payment status.
Order status.

This information is usually stored in a database.

For example, the order status might initially be marked as pending and later updated to confirmed or shipped.

6. Result / Output

After the necessary checks and payment processing have been completed successfully, the application provides feedback to the customer.

For example:

text
Order confirmed!

Product: Selected Product
Quantity: 2
Total: 100,000

Thank you for shopping with us.


This confirmation is the output produced by the system.

It lets the customer know that the order has been successfully placed.

Final Challenge: Explain the Whole System in My Own Words

Complete the chain:

text
Customer
    ↓
Customer Input
    ↓
Application / Program
    ↓
Instructions
    ↓
Data Processing
    ↓
Stored Data
    ↓
Result / Output

Questions and Answers

1. What is the computer doing?

The computer is receiving information, following instructions, processing data, storing important details, and producing results. It handles the different tasks needed to complete the customer's order.

2. What is the program doing?

The program provides the instructions that control how the online store works. It tells the computer how to receive orders, check product availability, calculate prices, process payments, and save order information.

3. What data is involved?

The data includes customer details, product information, quantity, price, delivery address, and payment information.

4. What instructions are being executed?

The instructions include checking the selected product, confirming its availability, calculating the total cost, validating customer details, processing payment, and saving the order.

5. What is the output?

The output is the information presented to the customer after processing. This could be an order confirmation showing the product, quantity, total amount, and order status.

6. What information might need to be stored for the system to remember the order?

The system needs to store the customer's details, product information, quantity, total amount, payment status, delivery address, and order status.

Without storing this information, the online store might not be able to retrieve the order or keep track of its progress.

My Understanding

An online store is more than just a website where people buy products. It is a system that receives information, processes it using instructions, stores important records, and produces results.

All these stages work together to make the shopping experience possible.

FINAL REFLECTION
Understanding How Computers Process Information

Statement:

"A computer does not understand the real world directly. It works with representations of information and follows instructions for processing those representations."

My Explanation

I understand this statement to mean that computers do not think or understand things the same way humans do. Humans can understand situations using experience, observation, and common sense, but computers depend on the information and instructions they are given.

For example, if I tell someone to make me breakfast, they might already have an idea of what I want. However, a computer would need specific instructions about the food to prepare, the ingredients to use, and the steps to follow.

The same idea applies to an ATM. When someone wants to withdraw money, the computer does not simply understand the person's intention. It follows a series of instructions to verify the card, check the PIN, confirm the account balance, and complete the transaction.

Computers also need information to be represented in specific ways. For example, a customer's name is stored as text, their age can be stored as an integer, and their account status can be represented as a Boolean value. These different data types help a program know how to handle the information.

The calculator exercise also shows how computers work. A user provides numbers as input, the program performs calculations on those numbers, and the computer displays the result as output.

In an online store, the same process happens on a larger scale. A customer provides information about the product they want to buy, the program processes the order, important details are stored, and the customer receives a confirmation.

From these examples, I have learned that computers depend on three important things: accurate information, clear instructions, and proper data representation.

A computer can only produce the expected result when the information it receives is correctly represented and the instructions it follows are properly designed.

Conclusion

This project has helped me understand that programming is not just about writing lines of code. Before writing code, a programmer needs to understand the problem, identify the information involved, break the problem into smaller steps, and decide how the computer should process that information.

I have also learned that a good program should consider situations where things might go wrong instead of only focusing on what happens when everything works perfectly.

Overall, the digital translator mindset is about taking ideas and problems that humans understand and turning them into clear instructions and data that a computer can process.