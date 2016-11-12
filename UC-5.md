# Apply for job:
# UC-5:


## Brief Use Cases:
User selects “Apply for job” option. The system opens the UI. The user then enters the information about the job - and then, the system presents ad options - standard or premium. The user confirms Apply for job details. The user is asked for credit card details. The system confirms the ad. All details are saved to system database. 



## Casual Use Cases:

####** The things that could go wrong are: **
1.User left a field empty e.g. Location etc..
2.User fails to select option
3.User enters the wrong credit card details
4.To apply for job might not be applied



## Fully Dressed Use Case: 

**Actor:** User.

**Description:** This use case lets the user to advertise job on system.

**Interest:** user wants to advertise a job standard or premium.

**Precondition:** user must be registered in the system before starting this use case.

**Main Success Scenario**

	1. The user logs on to the system.

	2. The user selects an option to create new advertise job.

	3. The user enters this information- job type, job description, etc.,then selects the continue option.

	4. System presents ad options Ð standard or premium

	5. The user selects premium option 

	6. The user fills in credit card information

	7. The system authorizes (ad job) advertise purchase

	8. System confirms the ad.

	9. System send confirming email to user.

	10.The user logs out.

**Alternative: Authorization Failure** 
 	At step 6: System fails to authorize credit purchase.
	Allow user to re-enter credit card information and re-try

#### **Post-condition:** The user has applied the job on the system.

