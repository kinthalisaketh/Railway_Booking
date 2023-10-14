# Railway_Booking
Railway ticket booking system is implemented by C programming. It is as same as one can see while we are going for online ticket booking. The following series of steps are being followed while booking a railway ticket in this software-

The first step is to provide the total number of passengers and submit all the necessary details of the passengers. The next step is to enter the source and destination. A list of available trains will appear. Among them, the user has to choose one. The ticket value will be evaluated. The system will ask to enter the seat choice by showing the seat matrix. At last, a receipt will be generated on the screen. Approach:

The first step is to implement a structure for taking the details of the passengers, like name, gender, and age. Five functions are defined void details(int), void add_node(char, char, int), int seat(int), int cal(int, int, int), void bill(int, int) to work smoothly. There are three elements in the structure like two strings one for taking passenger name and gender and one integer for taking passenger age. Also, a structure pointer will be used which helps to link the next node of another passenger. It is similar to the linked list. Character arrays are defined and some integer arrays are defined globally. Take the number of passengers as input and these details are sent to the details() function. Execute a for loop to take details of each passenger. The details inputted by the user will be sent to the add_node() function. In the add_node function, every detail will store in a node for each passenger. These nodes will link each other. This is based on the linked list concept. Take the input for source place, destination place and it will give some choice of trains available. Based on that user has to give a choice. Then call the cal() function. In cal() function, the user has to give a choice for sleeper or a.c. class. If the user chooses a.c. class another three options will open where the user has to give another choice based on that the system will add 18% GST on the amount and make total amount. Call the seat() function where a seat matrix will be given to the user and the user has to choose a seat same with the number of passengers. At last, call the bill() function where the total bill amount with all the necessary details will be displayed. Below is the implementation of the above approach:

railwaybooking/README.md at
