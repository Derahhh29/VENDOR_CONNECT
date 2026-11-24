# PRODUCT REQUIREMENT DOCUMENT {PRD}
## Product Name:Vendor Connect
##Product Type:Food Delivery Application

---

## 1. Product Overview

An app or a website meant to be used to connect food vendors with students in Babcock university. It will contain the following:

1.**A student page:**On this page, the student can make and pay for their order. The payment will contain the price of the food, the price of delivery and a commission for the website.  It would also have a chat area where students can communicate with the delivery people as well as give reviews to a vendor they buy food from. They should also be able to share the location on where the food is to be delivered to.
2.**The vendor’s page:**It will be a separate page that allows the vendor to upload and update the list of their food (showing the price and quantity per day). The vendors would also be notified when payment has been made and the food has been ordered by the student. The website should also be able to accept payments for vendor premium programs, to put vendors in favorable positions on the student’s page and to give them greater priority. 
3.**The delivery Rider's page:**It should allow a delivery person to see the food ordered and the location where they will drop the food. It should also allow the delivery people to be able to communicate with the students.
The website would generate revenue through commissions, vendor subscriptions and ads.

---

## 2. Problem Statement

The problems are as a result of the reduced number of stalls or vendors in the school campus. Which include: 
1.Far distance to other established restaurants like Babcock Guest House and BUTH Canteen. 
2.Students have to go physically to buy food in inconvenient situations or they are forced to rely on untrustworthy middlemen or delivery people who take advantage of them when food is ordered. 
3.Vendors are also incapable of serving numerous people during rush hours due to lack of space and they can also not reach students who get discouraged to go to their shops due to the distance and the crowds present in their shops. 
**Proposed Solution**
Develop a food delivery application that provides students a centralized platform in which they can conveniently order food, secure payments and trck their delivery in real time.

---

## 3. Business Objectives

The primary objectives of the Food Delivery app are:
1.**Fast Delivery:** Keeping to delivery schedules to provide students  with their food at the stated time.
2.**Increase Revenue:** Generate business revenue through services, delivery fees and commissions from food vendors.
3.**High Customer Satisfaction:** Provide a convenient, user-friendly experience that encourages repeat orders.
4.**Build Brand Recognition:** Make the app the 1st choice for everyday food orders by students on campus without losing trust and quality delivery service.
5.**Building Strong Vendor Partnerships:** Working together with multiple food vendors and restaurants to maintain consistent meal quality, accurate orders to fulfill the needs of customers.
6.**Connecting Customers with Food Vendors:** Creating a platform that allows good vendors and restaurants to showcase their meals to customers and receive orders, helping them boost sales.

---

## 4. Target Users

The Food Delivery Application serves four core user groups across mobile and web platforms:

|Target Users|Current Coping & Gaps|Core Needs|
|---|---|---|
|Customers|DIstance to preferred vendor is long, facing slow replies, manual payment checks, and sometimes race against time {classes}.|Easy menu browsing, live availability, secure payments, and fast trackable delivery.|
|Restaurant Owners|Over-crowding of stalls, slow efficiency in sales and manual transfer verification.|Simple order management, easy menu updates, instant payment confirmation, and wider reach.|
|Delivery Riders|Not in use.|Instant delivery alerts, accurate customer locations, and clear route navigation.|
|Administrators| Manually review vendors, track payments, and settle disputes without a central system.|User/vendor management, real-time transaction monitoring, and fast complaint resolution.|
 
---

## 6. Functional Requirements

Functional Requirements describe what the system must be able do.
|ID|Functional Requirements|Description
|---|---|---|
|FR01|Account Creation|The system must allow users to create accounts using their details.| 
|FR02|User LOgin|The system must allow users to login to their accounts securely.|
|FR03|List of Restaurants|The system must display the list of the restaurants available.|
|FR04|Food Menu|The system must display the dishes available in each restaurants.|
|FR05|Shopping Cart|The system must allow users to add, remove and modify their individual cart.|
|FR06|Order Placement|Customers must be able to place food orders.|
|FR07|Payment Processing|The system must allow various means of payment not just a singular one.|
|FR08|Order Tracking and Notifications|The system must allow customers to track the progress of their orders and inform them of any changes.|
|FR09|Restaurant Management|The system must allow restaurant owners to be able to add, edit and remove dishes from the menu and price adjustments.|
|FR10|Delivery Management|Delivery personnel must be able to accept and manage delivery requests.|
|FR11|Admin Management|Administratorsmust be able to manage users, restaurants and transactions.|

---

## 7. Non-Functional Requirements

Non-Functional Requirements describe how the system should perform.
|ID|non-Functional Requirements|Description|
|NFR01|Performance|The application's main page should be loaded within 5 seconds for smooth use.| 
|NFR02|Security|The system should protect users' information and payment details.|
|NFR03|Reliabilty|The system should run optimally with minimal service interruption.|
|NFR04|Usabilty|The system interface should be simple, easy to operate and understand.| 
|NFR05|Scalability|The system should be able to support increasing amount of users without server crash.|
|NFR06|Compatability|The system should be able to run on various Operating systems.|
|NFR07|Maintainability|The software should be designed to be able to accomodate updates and maintainance requests.|
|NFR08|Data Authenticity|The system must ensure that orders and payments records remain accurate and consistent.|

---

## 8. Scope and Priorities

This section defines the features that will be developed and what their importance is.
#A.	Features that will be included in our mvp(minimum viable products): these features are all of high importance. 
1.**User sign up and log in:** Sign up allows users to create accounts for identification on the website, while login is used to access an account already created by the user . These are important features of high priority.
2.**Order cart:** This is a list of orders chosen by the user, it is essential for the user to be able to order more than one thing at a time, in order to prevent excessive and recurring orders.
3.**Search bar and discover:** This is essential for users to locate the dish and vendor of their choice instead of mindless scrolling. This is a very important priority of the website 
4.**Food menu and price listings:** The food menu is the major purpose of this business, and without the price listings the application is useless.
5.**User profile management:** This is where the settings, usernames, switch account, themes menu and so much more will be displayed.
6.**Order tracker:** This is for tracking already ordered goods by the buyer.
7.**Ratings and reviews:** Leaving a rating is important to enable buyers to discover good sellers.
8.**Buyer To Seller connections:** This is of major importance to the business, to reduce confusion and confirm addresses.

B. Low-No priority features(out of scope): the following features will not be included in our mvp

1.**Promotional orders and discounts:** Discounts is not a major reason for the creation of the business -low priority.
2.**AI food recommendations:** This simply is not a priority and is not a major part of the business.

---

## 9. Acceptance Criteria

Acceptance criteria specify the requirements that each feature must meet before it can be considered complete and ready for use.

|Feature|Acceptance Criteria|
|---|---|
|Account Creation|Users must be able to register by providing their name, email address, phone number and password.|
|User Authentication|The system must verify user credentials before granting access to their accounts.|
|Location Selection|Customers must be able to select or enter their delivery location to find available food services.|
|Restaurant Search|Customers must be able to search for restaurants using restaurant names or food categories.|
|Menu Management|Restaurants must be able to add, edit and remove food items, including their prices and descriptions.|
|Cart Management|Customers must be able to review selected items and modify their quantities before checkout.|
|Checkout Process|Customers must be able to review their orders, delivery information and total charges before submission.|
|Order Confirmation|The system must generate an order confirmation and notify the customer after successful placement.|
|Payment Processing|Customers must be able to complete payments through the available payment methods.|
|Delivery Tracking|Customers must be able to monitor delivery progress and receive updates on their orders.|
|Order Management|Restaurant administrators must be able to view incoming orders and update their preparation status.|
|Customer Feedback|Customers must be able to rate their dining and delivery experience after an order is completed.|

**Example of an Acceptance Criterion Feature: Delivery Tracking.**
The feature will be accepted when:

1.The customer can access the tracking page for an active order.
2.The system displays the current order status.
3.The delivery rider’s assigned details are available to the customer.
4.The system updates the customer when the delivery status changes.
5.The customer receives confirmation when the order has been delivered.
6.The tracking information corresponds to the correct order.

---

## 10. Assumptions And Open Questions

 ### A. Assumptions 
The development of the application is based on the following assumptions:
1.Restaurants are willing to register their business on the platform.
2.Customers have access to a good internet.
3.A trustworthy third party payment gateway should be united  
4.Riders are available to fulfil customers orders
5.Customers would have valid and accurate delivery addresses 

### B. Open questions 
These are questions that must be answered before or during development. 
|No. | Open questions | why it matters |
|---|---|---|
|1| Would customers complains and refunds be attended to? |
|2| How would customers make payment? |
|3| Would delivers be handled by trusted and skilled riders? |
|4| Who sets and receives delivery charges? |
|5| How would vendor verify that an order has been collected by the correct rider? |
|6| What customers information is order necessary for a successful delivery? |
|7| what would happen when a vendor rejects a customers order? |