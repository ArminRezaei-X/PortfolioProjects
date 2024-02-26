# Armin's Real Estate Helper
#### Video Demo:  <https://youtu.be/osZm0fTyNig>
#### Description:

1: login And Sign Up Section
The login menu has three options:
1. Sign up
2. Sign in
3. Exit
At this menu, (and other menus) the available options for the user to choose will be displayed and the user's chosen option will be recieved in the form of a number.

1-1: Sign Up
In this section, the users of must create an account for themselves (this means the employees of the real estate company).
For this purpose, the user's information will be recieved and stored in a separate file (informations of users.txt).
This program is multi-user, so it's able to manage multiple users but at different times.
The information stored from the user includes at the following:
. Username
. Name
. Family
. National code
. Mobile number
. Email
. Password

1-2: Sign In 
In this section, the user must first enter his username and then his password. The program will check the correctness of the username and password, and if approved, the user will be allowed to log in.
If the username or password is not in the file and does not match, the user will be asked to try again (3 attempts).

1-3: Exit 
By choosing this option, the user will exit the entire program.


2: Main Menu
After the successful authentication procedure, the user enters the program and the main menu including the following items is displayed:
. Register new information
. Delete information
. Reports
. User account settings
. Log out (return to the previous menu)
The user's choice will be obtained by receiving a character.

2-1: Register New Information
One of the parts of the program is to register properties that are newly introduced to our hypothetical company.
Therefore, the user of the program sometimes needs to register a new property in the program, and he must choose this option.
But before that, the type of information we want to record will be determined.
After entering this section, the following will be displayed:
. Sale
. Rent
. Back to menu
The user must choose one of these two based on the type of new property.

2-1-1: Sale
After the user has indicated that they want to list a property for sale, the following options will be displayed for the user to choose from:
. House registration
. Office registration
. Land registration
. return to the previous menu
After entering each of the three sections related to sales registration, the desired information for each property must be entered.

2-1-1-1: House Registration For Sale
In this section, the user must register the details of the newly introduced house property to the company in the program.
This information is received from the user and stored in a file (House-Sell.txt).
The information is as follows:
. Municipal district indicating the property's location in the city
. The exact address of the property
. Type of property (apartment or villa)
. Building age
. The size of the infrastructure
. Floors
. The size of the main land of the property
. Contact number of the owner
. Number of bedrooms
. Selling price

2-1-1-2: Office Registration For Sale
In this section, the user must register the details of the office property to the company in the program.
This information is received from the user and stored in a file (Office-Sell.txt).
The information is as follows:
. Municipal district indicating the property's location in the city
. The exact address of the property
. Type of property (official administrative document, or just administrative position)
. Building age
. The size of the infrastructure
. Floors
. The size of the main land of the property
. Contact number of the owner
. The number of office rooms
. Selling price

2-1-1-3: Land Registration For Sale
In this section, the user must register the details of the land to the company in the program.
This information is received from the user and stored in a file(Land-Sell.txt).
The information is as follows:
. Municipal district indicating the property's location in the city
. The exact address of the land
. Type of land (agricultural or urban)
. Land size
. The contact number of the owner
. Selling price


2-1-2: Rent
This section is similar to sales registration and will include the following
After the user has specified that they want to list a property for rent, the following options should be displayed for the user to choose from:
. House registration
. Office registration
. Land registration
. Return to the previous menu
After entering each of the three sections related to the rental registration, the desired information for each property must be entered.

2-1-2-1: House Registration For Rent
The information that will be stored in the program for House property for rent is the same as for House property for sale,
with this difference that instead of the sale price, two separate figures will be recorded, one for the mortgage amount and the other for the monthly rent amount.

2-1-2-2: Office Registration For Rent
The information that will be stored in the program for Office property for rent is the same as for Office property for sale,
with this difference that instead of the sale price, two separate figures will be recorded, one for the mortgage amount and the other for the monthly rent amount.

2-1-2-3: Land Registration For Rent
The information that will be stored in the program for land property for rent is the same as for land property for sale,
with this difference that instead of the sale price, two separate figures will be recorded, one for the mortgage amount and the other for the monthly rent amount.


2-2: Delete Information
The title of this section should actually be: "Archiving properties", but we don't want to confuse the end user.
This means that the details of a property will never be deleted from the system.
Rather, when the desired property is sold (or rented), it will be archived.


2-3: Reports
This is the most important part of this program. Because the user needs to report many times and refers to this section.
In this section, various reports will be presented to the user. Example:
. The number of properties in the system
According to the type of property (for example, Houses for rent, or Offices for sale, or lands...)
. List of properties available in a specific municipal area
. List of properties with a specific building age (for example, building age between 3 and 6 years)
. List of properties with specific infrastructure size (for example between 40 meters and 65 meters)
. List of properties with special price (for example between 2 billion and 4 billion tomans)
. List of all residential properties with a specific number of bedrooms (for example, 2 bedrooms)
. The total value of the properties registered in the system for sale (sum of the total price of the system inventory to present to a strict administrator!).
. The list of system users who have registered properties in the system.
For example, the manager wants to know which user of the system has registered more properties in the system and which user has the least activity.
This option will be active and displayed only for the admin user.
. List of rental properties with a specific range for mortgage and rent. (Both parameters will be checked together.)
. The list of properties registered in the system in a certain period.
The manager wants to know, for example, what items were recorded in the system in the last 3 weeks?
. A list of all the apartments on a certain floor (for example, only apartments located on the third floor).
. The list of properties removed in a certain period of time.
This report is active only for admin.
. The list of system users and the date of the last activity of each user.
This report is active only for admin.


2-4: User Account Settings
In this section, the user of the program is able to change his profile information, including the password.
Users cannot change their username. They can change the rest of the informations.


2-5: Log Out
By selecting this option, the program exits the user's account and returns to the Login page.
This program is multi-user. So when a user leaves his account, the program will not be closed and another user can log in.
​
​
​
