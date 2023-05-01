Download Link: https://assignmentchef.com/product/solved-cis-1111-restaurant-functions
<br>
<p class="ui header product-top-header" title="CIS 1111 Programming Topic 10 – Restaurant Functions Solution">Write a menu-driven C++ program for food purchases at the baseball stadium’s restaurant. The main program will loop allowing the user to select food items from the menu adding each item to the bill, terminating when the user selects the “End order” item. The program will then calculate and display the total bill with tax (.065) and tip (.20); tip is calculated on the pretax bill. The program also needs to collect payment and calculate change due.

The program needs to validate that the user has entered a valid menu selection and that the amount tendered is enough to cover the bill.

HINT: Use the menu-driven program on pages 318-319 of our textbook as a model.

Requirements:

1.       Functions :

a.       Define a void function without parameters to display the food menu and prices

b.       Define a void function with 4 parameters (bill, totBill, tax, tip) to display the bill

c.       Define a void function with 2 parameters (totBill, amtTendered) to calculate and display the change due

2.       Global variables may not be used. All variables used in functions must be passed by parameters or declared locally.

3.       Program must be menu-driven

4.       Input validation for menu item choice and amount tendered.

5.       Verify that the customer tendered an amount that is equal to or greater than the total bill.

6.       Output must be labelled and easy to read as shown in the sample output below. Only display 2 decimal points when displaying Total Amount Due and Change Due.

7.       Program must be documented with the following:

a.       // Name

b.       // Date

c.       // Program Name

d.       // Description

See the sample output on the following page.

Sample Output:

Baseball Game Snack Menu

1 – Hamburger                  $6.00

2 – Hotdog                          $4.50

3 – Peanuts                        $3.75

4 – Popcorn                        $5.50

5 – Soda                               $2.80

6 – Chips                              $1.00

7 – Water                            $2.00

8 – End order

Enter menu item: 2

Enter menu item: 5

Enter menu item: 6

Enter menu item: 9

Incorrect menu selection, please reenter: 8

Bill = $8.30

Tax = .54

Tip =  $1.66

Total amount due: $10.50

Amount tendered: $10.00

Amount paid is not enough to cover bill, please enter new amount: $15.00

Change due: $4.50

Submit:

Zipped folder named LastNameFirstNameCIS1111NameOfAssignment which contains:

1.       Your .cpp file

2.       Screen shots of your code and output