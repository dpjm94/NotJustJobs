# Advertise rental 
# UC-6:


## Brief Use Case: 
This use case allow user to advertise rental on the system. The user able to enter details about rental such as location, price.

## Casual Use Case: 
User selects “Advertise rental” option. The system opens the UI. The user then enters the information about the rental - location, rent or buy. and then The system presents ad options - standard or premium.The user confirms Advertise rental details. The user is asked for credit card details. The system confirms the ad. All details are saved to system
database. 

####** The things that could go wrong are: **
1. User fails to select option
2. User enters the wrong credit card details
3. The system fails to put advertise job post up.



## Fully Dressed Use Case: 

**Actors:** User.

**Description:** This use case lets the user to advertise rental 

**Interest:** user wants to advertise a rental : sale or rent.

**Precondition:** user must be registered in the system before starting this use case

**Main Success Scenario:**

	1.	The user logs on to the system.

	2.	The user selects an option to create new rental

	3.	The user enters this information - rental details :into ad title, price, ad description, contact preferences, ad type - Wanted or sale, subsection house, apartment, etc. 

	4.	The System presents ad options Ð standard or Premium.

	5.	The user selects standard option 

	6.	The user fills in credit card information

	7.	The System authorize (rental) advertise purchase.

	8.	The System confirms the ad.

	9.	The user logs out.

	10.	The System send confirming email to user.

**Authorize: Authorization**
	At step 6: System fails to authorize credit purchase.
	Allow User to re-enter credit card information and re-try

#### **Post-condition:** The user has advertise rental up on the system.
