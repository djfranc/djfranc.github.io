# The Shopping List Calculator
(Tax Calculator)

##### Link to Tax Calculator repo [here](https://github.com/djfranc/Shopping-List-Tax-Calculator)


### Description:

**Difficulty: 1**

**Description:** Create a program which asks the user to enter in a dollar value and the current tax percentage. Then print out the subtotal along with the total plus tax (grand total).

**Tips:** This is a very simple program where you collect the value from the user, have the user enter in a tax value, add the tax to the total and print out the result. If the value the user enters is $1.00 and the tax is 5% then the total is $1.05.

**Added Difficulty:** Build a GUI for this program where the user can enter in multiple prices, adds them up and then calculates the tax. Perhaps some of the items won’t be taxed based on the item type (like food).

--------------

##### **Approach:** 
 
The first sentence of the description describes the input variables, the second the output variables.
From this we have an idea of all the information that we can work with and manipulate to get the desired output result.

Input:
- Dollar value of each item 
- Tax amount

Output:
- Total (Tax+Sum)
- Subtotal (Sum)

From here we need to realize the functions we need to arrive at the necessary output. In this case we are only adding values and multiply for the tax.

If you are planning on solving the **Added Difficulty** portion with the introduction of GUI elements, I highly recommend having the GUI present from the start and working towards a solution through it instead of through a console window. 

Note: For problems of Level 1 Difficulty problem I avoid using intermediate concepts unless I clearly see a place where they can easily be understood and it simplifies the process.

--------------

## **Problem Solving**

There are multiple ways to problem solve for the GUI functionality. 
One of my favorite methods is to create small but simple user stories.

**USER STORIES:** 

Actor(s): User 

Stories:
- As a user I want an add button to add more than one item.
- As a user I want to be able to clear and restart my calculations.
- As a user I want to be able to take off taxes on certain items.

Keeping the stories and functionality reasonable for a Level 1 project.
