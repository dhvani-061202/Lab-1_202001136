# Lab-1_202001136
## IT314-Software Engineering Lab-1
### Identifying Functional and Non-Functional Requirements

#### Q.1. Identify FRs and NFRs:

##### The Functional Requirements observed from the description for the Library Information System (LIS) are as follows:
1. The system should be a web application (using HTML 5) which runs only within the institute LAN.
2. The employees and students of the institute are allowed to issue or return books through the system.
3. The member should have their own personal username or email id and password for logging into the system.
4. Any non-member should be able to browse/search books online through the system.
5. The system should neatly list all the books available under their corresponding subgroup or topic for proper organization.
6. Enable members (students and employees) to borrow or return a book.
7. On issuing a book, the details about which member has issued the book, what is the deadline and which subgroup it is from should be stored into the system and shared to the user through mail or a notice in their personal feed on the system.
8. Enable a member to extend the date of his/her borrowing if no other booking for that particular book is not made.
9. Provide administrative privileges to librarian to perform the day-to-day transactions mentioned below easily:
  	* Enter a new record in the system if a new book is purchased.
    * Remove a record from the system if the corresponding book is taken off the shelf.
    * The librarian should have access to all the latest data regarding the issuing or returning of books.
10. Additional features like newsletter or articles on the member’s interests can be shred through mail or in their personal feed on the system. 
11. The system should work on multiple working environments like Windows, or any other OS smoothly without lagging the end device.
12. In case of a system failure due to power failure or in a server shutdown, the system should store all the information changed before the shutdown with the help of a rollback mechanism and return to its last working condition.  
13. No sensitive information like data regarding the system or the users’ personal data should leak and utmost privacy and security should be maintained.
14. The confidential information should not be stored in plain text.


##### The Non-Functional Requirements observed from the description for the Library Information System (LIS) are as follows:
1. Usability:
    * The system should be easy-to-use with a user-friendly Graphical User Interface (GUI). 
2. Security:
    * The storing of confidential data like passwords should be maintained with utmost security. 
    * The users should be logged out automatically by the system after a certain time duration of inactivity.
3. Scalability:
    * The system should be able to scale its performance according to the number of users accessing it.
4. Maintainability:
    * The system should be easy to maintain occasionally. 
5. Reliability:
    * The system should be reliable enough to handle large amounts of data.
6. Performance:
    * The system should perform all the valid tasks desired by a user in reasonable time. 

#### Q.2. Identify scope, features and non-functional aspects of the following problem.

##### The scope for the mentioned description is:
The application created will use AI recognize key sound events for immediately alerting the user.

##### The features for the mentioned description is:
* The application uses artificial intelligence to recognize key sound events such as car horns and babies. 
* On receiving such a sound, the user is immediately alerted. 

##### The non-functional aspects for the mentioned description are:
* This application is an impactful solution for people suffering from disabling hearing loss. 
* This application is optimized for Android with low-latency.
* Continual logging is required for detecting sounds and sending immediate alerts. 
* If the application is down due to power failure or any other reason, it should store the conditions before failure and return to initial state.
* The application should not drain too much battery and should not lag the device its working on.
     
