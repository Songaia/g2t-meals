

###### Use Cases
Account Creation<br>  User Login<br> 
task transfer <br>
Signup<br>Request Plate<br>Receive Late Notice<br>







Use Case Title: Account Creation<br> 	  Actors: User <br> 	  Trigger: User Wants to create an account<br> 	  Pre-condition: User does not yet have an account<br> 	  Post-condition: User is logged in<br>       Basic Flow:

1. User selects the create account option
2. User enters their account information (name, email, phone number, etc) as prompted
3. User's account is created
4. User is logged in  

Alternate Flow - Step : 2<br>

2a. User's account info already exists

3a. User is prompted to **login**

piuuninitititti



Use Case Title: Login<br> 	  Actors: User <br> 	  Trigger: User wants to log in to the app<br> 	  Pre-condition: User is not already logged in<br> 	  Post-condition: User is logged in to their account<br>       Basic Flow:

1. User enters their name and password
2. User selects the login option
3. User is logged in

Alternate Flow - Step 2: 

2a. User's name is incorrect

3a. User is prompted to input their name again or **create an account**



Use Case Title: Signup <br> 	  Actors: User <br> 	  Trigger: User wants to sign up for a task<br> 	  Pre-condition: User can sign up<br> 	  Post-condition: User successfully signed up for a task<br>       Basic Flow:

1. User selects an empty task
2. User is signed up for that task

Alternate Flow - Step 1: <br>

1a. User selects an occupied task

2a. User is prompted to sign up for an open task

3a. User signs up for an open task



Use Case Title: Request task transfer <br> 	  Actors: Requestor, Requestee<br> 	  Trigger: Requestor wants to transfer their current task to requestee<br> 	  Pre-condition: Requestor has a task<br> 	  Post-condition: Requestor's task is transferred to Requestee<br>       Basic Flow:

1. Requestor selects their current task to transfer
2. Requestor chooses Requestee's name from the transfer list
3. Requestor sends the transfer request to Requestee
4. Requestee accepts the transfer request
5. Requestee receives Requestor's task

Alternate Flow - Step 4: <br>

4a. Requestee denies the transfer request

4b.  Requestor chooses another candidate for the transfer

Exception - Step 4: <br>

4a. Requestee denies the transfer request

4b.  Requestor fails to transfer their task





Use Case Title: Request Plate<br> 	  Actors: User<br> 	  Trigger: User wants to sign up for a plate<br> 	  Pre-condition: User must have an account<br> 	  Post-condition: User has a plate saved for them <br>       Basic Flow:

1. User selects date(s) on which to receive a plate

2. a plate is saved for the user

   





Use Case Title: Receive Late Notice<br> 	  Actors: User <br> 	  Trigger: User has not yet signed up for a task<br> 	  Pre-condition: User has an account<br> 	  Post-condition: User is signed up for a task<br>       Basic Flow:

1. User receives a reminder notification
2. User **Signs up for a task**


