\#Requirements and Conceptual Model
Timothy Yip, Stephanie Y. Lopez Chavoya

Part B:

1. Who is the end user?
Lana
2. What does the end user need to be able to do?
Needs to be able to keep track of information on each customer, dog, appointment schedules, and payment.
3. What categories of data to track?
Customer information, dog information, appointment information, and payment information.

Part C:

1. Customer Information
* Customer ID
* Customer Name
* Phone Number
* Email
* Address
2. Dog Information
* Dog ID
* Dog Name
* Dog Breed
* Age
* Weight
* Medical/Allergies
* Instructions
* Customer ID
3. Appointment Information
* Appointment ID
* Date
* Start Time
* End Time
* Appointment Status
* Dog ID
4. Payment Information
* Payment ID
* Customer ID
* Amount Due
* Payment Method
* Payment Date
* Payment Status
* Appointment ID

\#Logical Model

a) What should be the main entities in your database?
Customer information, dog information, appointment information, and payment information.

b) What attributes belong to each of those entities? What are the pieces of information that the record should include?
For Customer Information:

* Customer ID, unique ID for each customer
* Customer Name, name of the customer
* Phone Number, preferred number to contact the customer
* Email, customer's email address
* Address, customer's home address
For Dog Information:
* Dog ID, unique ID for each dog
* Dog Name, name of dog being walked
* Dog breed, breed of dog being walked
* Age, age of dog being walked
* Weight, weight of dog being walked
* Medical/Allergies, any important medical information or allergies the dog has
* Instuctions, any special requests or instructions from the customer
* Customer ID, unique ID for each customer
For Appointment Information:
* Appointment ID, unique ID for each appointment made
* Date, date of the appointment
* Start Time, time the walk starts
* End Time, time the walk ends
* Appointment Status, if the appointment is upcoming, in progress, completed, or cancelled
* Dog ID, unique ID for each dog
For Payment Information
* Payment ID, unique ID for each payment recieved
* Customer ID, unique ID for each customer
* Amount Due, price of appointment
* Payment Method, form of payment
* Payment Status, if payment is unpaid, pending, paid in full, partially paid, or refunded
* Appointment ID, unique ID for each appointment made

c) What entities will have relationships to each other?

* Customer to dog
* Customer to appointment
* Customer to payment
* Dog to appointment
* Appointment to payment

d) Can you identify any possible many-to-many relationships between your tables that will need to a resolving table?
Assuming there are multiple appointments with multiple dogs and the same dog appearing in different appointments there will be a many to many relationship that'll need a resolving table.





Notes:

A) Me and Tim have the same fields in our diagrams, and we also contain the same relationships. Our Diagrams look very similar.

B) Our Diagrams are different through the formatting; such as mines has space for what type of key the field requires such as PK, INT, and FK. And a explanation for those differences is, I created my own vs generating it. So I was able to have exact control over all fields and styles. And the pro of this is I have exact control on how I want my diagram to look. And a con is, it is more time consuming to create your own.

