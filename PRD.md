# PRODUCT REQUIREMENT DOCUMENT {PRD}
## Product Name:Vendor Connect
## Product Type:Food Delivery Application

---

## 1. Product Overview

An app or a website meant to be used to connect food vendors with students in Babcock university. It will contain the following:<br>

1.**A student page:** On this page, the student can make and pay for their order. The payment will contain the price of the food, the price of delivery and a commission for the website.  It would also have a chat area where students can communicate with the delivery people as well as give reviews to a vendor they buy food from. They should also be able to share the location on where the food is to be delivered to.<br>
2.**The vendor’s page:** It will be a separate page that allows the vendor to upload and update the list of their food (showing the price and quantity per day). The vendors would also be notified when payment has been made and the food has been ordered by the student. The website should also be able to accept payments for vendor premium programs, to put vendors in favorable positions on the student’s page and to give them greater priority.<br>
3.**The delivery Rider's page:** It should allow a delivery person to see the food ordered and the location where they will drop the food. It should also allow the delivery people to be able to communicate with the students.<br>
The website would generate revenue through commissions, vendor subscriptions and ads.

---

## 2. Problem Statement

The problems are as a result of the reduced number of stalls or vendors in the school campus. Which include:<br>

1.Far distance to other established restaurants like Babcock Guest House and BUTH Canteen.<br>
2.Students have to go physically to buy food in inconvenient situations or they are forced to rely on untrustworthy middlemen or delivery people who take advantage of them when food is ordered.<br>
3.Vendors are also incapable of serving numerous people during rush hours due to lack of space and they can also not reach students who get discouraged to go to their shops due to the distance and the crowds present in their shops. 

**Proposed Solution**
Develop a food delivery application that provides students a centralized platform in which they can conveniently order food, secure payments and trck their delivery in real time.

---

## 3. Business Objectives

The primary objectives of the Food Delivery app are:<br>

1.**Fast Delivery:** Keeping to delivery schedules to provide students  with their food at the stated time.\
2.**Increase Revenue:** Generate business revenue through services, delivery fees and commissions from food vendors.\
3.**High Customer Satisfaction:** Provide a convenient, user-friendly experience that encourages repeat orders.\
4.**Build Brand Recognition:** Make the app the 1st choice for everyday food orders by students on campus without losing trust and quality delivery service.\
5.**Building Strong Vendor Partnerships:** Working together with multiple food vendors and restaurants to maintain consistent meal quality, accurate orders to fulfill the needs of customers.\
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

## 5. StakeHolders

The key stakeholders involved in the development and operation of the Food Delivery Application are:\
1.**Customers:** Individuals who use the application to browse restaurants, place orders, make payments and track deliveries.\
2.**Restaurant Owners/Vendors:** Responsible for managing restaurant profiles, uploading menus, receiving orders and preparing meals.\
3.**Delivery Riders:** Responsible for collecting orders from restaurants and delivering them to customers.\
4.**System Administrator:** Responsible for managing users, monitoring activities, resolving disputes and maintaining the platform.\
5.**Development Team:** Software developers, UI/UX designers and testers responsible for building, designing and maintaining the application.\
6.**Payment Service Providers:** Third-party organizations responsible for processing online transactions securely.

## 6. User Stories 

These stories cover four roles on the Babcock campus app, and every story has a priority and a testable acceptance criterion.\
•**Format:** As a <role>, I want <action> so that <benefit>.\
•**IDs:** C = customer, R = restaurant, D = delivery rider, A = administrator.\
•**High:** the app cannot launch without it. Medium: improves the experience. Low: can wait for a later version.

### Customer stories (students and staff)
Customers need to order from open vendors and get food delivered to their hall or office; 7 of these 15 stories are High priority.
|ID|User story|Priority|Acceptance criteria|
|---|---|---|---|
|C01|As a student, I want to sign up with my Babcock email or matric number so that only campus members can order.|High|Only valid Babcock emails or matric numbers are accepted; the account is verified by code before the first order.|
|C02|As a student, I want to save my hall and room number as my delivery address so that I don't retype it every order.|High|Hall is chosen from a list; room number is required; the saved address is preselected on the next order; more than one address can be saved (e.g. hall and department).|
|C03|As a customer, I want to see only vendors that are currently open, with an estimated prep time, so that I don't order from a closed kitchen.|High|Closed vendors are hidden or greyed out; each open vendor shows its prep time; vendors can be filtered by food category.|
|C04|As a customer, I want to view menus with prices and see sold-out items so that I order only what is available.|High|Each item shows name, description and price; sold-out items cannot be added to the cart.|
|C05|As a customer, I want to add, remove and change quantities in my cart so that I can order several items at once.|High|Cart total updates immediately after every change; the cart is kept if the app closes.|
|C06|As a customer, I want to place an order so that the vendor starts preparing my food.|High|	Order needs at least one item and a valid delivery address; total cost is calculated correctly; a unique order ID is generated; the vendor is notified.|
|C07|As a customer, I want to pay by card or bank transfer (and cash on delivery, if approved) so that I can use the method I have.|High|Successful payment shows a confirmation; a failed payment shows a clear message and a retry option; I am never charged twice for one order.|
|C08|As a customer, I want to cancel an order before the vendor accepts it so that I'm not stuck with food I no longer want.|Medium|Cancel is available only while the status is Placed; a refund confirmation is shown; after acceptance the button is disabled with an explanation.|
|C09|As a customer, I want to track my order status so that I know when to meet the rider.|Medium|Statuses shown: Placed, Accepted, Preparing, Picked up, Delivered; the current status updates without a manual refresh.|
|C10|As a customer, I want notifications when my order status changes so that I don't have to keep checking the app.|Medium|A notification is sent on every status change; Picked up and Delivered notifications arrive within 1 minute of the change.|
|C11|As a customer, I want to call or message my rider if they can't find me so that the delivery isn't missed.|Medium|Contact option appears only while the order is Picked up; the rider's number is hidden after delivery.|
|C12|As a customer, I want to reorder from my history so that repeat meals take seconds.|Medium|Order history lists past orders with date and total; Reorder fills the cart with the same items at current prices.|
|C13|As a customer, I want to rate and review a vendor after delivery so that others know what to expect.|Medium|Rating is allowed only for delivered orders; one rating per order; the average rating is shown on the vendor page.|
|C14|As a customer, I want to apply a promo code so that I can save money.|Low|A valid code reduces the total and shows the discount; an expired or invalid code shows an error.|
|C15|As a customer, I want to earn loyalty points on repeat orders so that I'm rewarded for staying.|Low|Points are added after each delivered order; the balance is visible in my profile.|

 ### Restaurant and vendor stories
Vendors need to control what customers can order and when; 6 of these 10 stories are High priority.
|ID|User story|Priority|Acceptance criteria|
|---|---|---|---|
|R01|As a vendor, I want to create a profile with my name, campus location and contact so that students can find me.|High|Profile is submitted for admin approval; it is not visible to customers until approved.|
|R02|As a vendor, I want to add, edit and remove menu items with prices so that customers see my current menu.|High|Changes appear in the customer app within 1 minute; each item has a name, price and optional photo.|
|R03|As a vendor, I want an alert for every new order so that I can start cooking quickly.|High|Alert shows items, quantity, delivery hall and payment status; the order stays highlighted until it is accepted or rejected.|
|R04|As a vendor, I want to accept or reject an order so that customers aren't left waiting.|High|Rejecting requires a reason; the customer is notified immediately and refunded if already paid.|
|R05|As a vendor, I want to update an order to Preparing and Ready for pickup so that the rider and customer know its progress.|High|Each status change is visible to the customer and rider; statuses cannot move backwards.|
|R06|As a vendor, I want to mark items as sold out so that customers can't order food I don't have.|High|A sold-out item cannot be added to a cart; it can be restored with one tap.|
|R07|As a vendor, I want to set my opening hours and prep time so that customers see accurate availability.|Medium|The vendor shows as closed outside its hours; the prep time estimate appears on the vendor card.|
|R08|As a vendor, I want to see my daily sales so that I can track my earnings.|Medium|Dashboard shows orders and revenue per day, and filters by date range.|
|R09|As a vendor, I want to reply to customer reviews so that I can respond to complaints.|Low|A reply appears under the review; each review allows one reply.|
|R10|As a vendor, I want to create promotional offers so that I can attract more customers.|Low|A promotion has a start date, end date and discount; it expires automatically.|

### Delivery Rider Stories 
Riders need clear jobs and clear drop-off points on campus; 4 of these 8 stories are High priority.
|ID|User story|Priority|Acceptance criteria|
|---|---|---|---|
|D01|As a rider, I want to go online or offline so that I only get requests when I'm available.|High|Requests are sent only to online riders; going offline is blocked while a delivery is in progress.|
|D02|As a rider, I want to accept or decline delivery requests so that I choose the jobs I can do.|High|A request shows the vendor, drop-off hall and delivery fee; once one rider accepts, it disappears for the others.|
|D03|As a rider, I want to see the pickup point and the hall, building and room for drop-off so that I can find the customer quickly.|High|Both locations are shown on a map and as text; the customer's room number is visible only after I accept.|
|D04|As a rider, I want to mark an order as Picked up and Delivered so that customers can follow progress.|High|Each update notifies the customer; Delivered requires the customer's confirmation code.|
|D05|As a rider, I want to call or message the customer when I can't find them so that I can complete the delivery.|Medium|Contact is available only during an active delivery.|
|D06|As a rider, I want to report a problem (wrong order, customer unreachable) so that I'm not blamed for it.|Medium|The report is sent to an administrator with the order ID and time.|
|D07|As a rider, I want to see my completed deliveries and earnings so that I can track my income.|Medium|Earnings are listed per delivery and totalled per day and week.|
|D08|As a rider, I want to cancel an accepted job in an emergency so that the order can go to another rider.|Low|The order is reassigned automatically; repeated cancellations are logged for admin review.|

### Administrator Stories
Administrators keep the platform trusted by vetting vendors and riders and resolving money disputes; 4 of these 7 stories are High priority.
|ID|User story|Priority|Acceptance criteria|
|---|---|---|---|
|A01|As an administrator, I want to approve or reject vendor and rider applications so that only trusted people join.|High|New accounts stay inactive until approved; a rejection records a reason.|
|A02|As an administrator, I want to suspend and reactivate accounts so that I can remove bad actors.|High|A suspended user cannot log in or receive orders; the action is logged with date and reason.|
|A03|As an administrator, I want to monitor all transactions and see failed payments so that I can fix payment problems.|High|Every payment shows order ID, amount, method and status; failed payments can be filtered.|
|A04|As an administrator, I want to issue refunds so that customers are repaid for cancelled or wrong orders.|High|A refund is linked to its order, needs a reason, and the customer is notified.|
|A05|As an administrator, I want to view complaints with the full order history so that I can settle disputes fairly.|Medium|A complaint shows customer, vendor, rider, timeline and payment; its outcome is recorded.|
|A06|As an administrator, I want to set delivery fees and vendor commission so that the platform earns revenue.|Medium|Fees and commission can be changed without a new app release; changes apply only to new orders.|
|A07|As an administrator, I want daily reports on orders, revenue and top vendors so that I can see how the platform is performing.|Low|Report covers a chosen date range and can be exported.|
 
---

## 7. Functional Requirements

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

## 8. Non-Functional Requirements

Non-Functional Requirements describe how the system should perform.
|ID|Non-Functional Requirements|Description|
|---|---|---|
|NFR01|Performance|The application's main page should be loaded within 5 seconds for smooth use.| 
|NFR02|Security|The system should protect users' information and payment details.|
|NFR03|Reliabilty|The system should run optimally with minimal service interruption.|
|NFR04|Usabilty|The system interface should be simple, easy to operate and understand.| 
|NFR05|Scalability|The system should be able to support increasing amount of users without server crash.|
|NFR06|Compatability|The system should be able to run on various Operating systems.|
|NFR07|Maintainability|The software should be designed to be able to accomodate updates and maintainance requests.|
|NFR08|Data Authenticity|The system must ensure that orders and payments records remain accurate and consistent.|

---

## 9. Scope and Priorities

This section defines the features that will be developed and what their importance is:
# A.	Features that will be included in our MVP(minimum viable products):These features are all of high importance.
1.**User sign up and log in:** Sign up allows users to create accounts for identification on the website, while login is used to access an account already created by the user . These are important features of high priority.\
2.**Order cart:** This is a list of orders chosen by the user, it is essential for the user to be able to order more than one thing at a time, in order to prevent excessive and recurring orders.\
3.**Search bar and discover:** This is essential for users to locate the dish and vendor of their choice instead of mindless scrolling. This is a very important priority of the website.\
4.**Food menu and price listings:** The food menu is the major purpose of this business, and without the price listings the application is useless.\
5.**User profile management:** This is where the settings, usernames, switch account, themes menu and so much more will be displayed.\
6.**Order tracker:** This is for tracking already ordered goods by the buyer.\
7.**Ratings and reviews:** Leaving a rating is important to enable buyers to discover good sellers.\
8.**Buyer To Seller connections:** This is of major importance to the business, to reduce confusion and confirm addresses.

# B.Low-No priority features(out of scope):The following features will not be included in our MVP

1.**Promotional orders and discounts:** Discounts is not a major reason for the creation of the business -low priority.\
2.**AI food recommendations:** This simply is not a priority and is not a major part of the business.

---

## 10. Acceptance Criteria

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

1.The customer can access the tracking page for an active order.\
2.The system displays the current order status.\
3.The delivery rider’s assigned details are available to the customer.\
4.The system updates the customer when the delivery status changes.\
5.The customer receives confirmation when the order has been delivered.\
6.The tracking information corresponds to the correct order.

---

## 11. Assumptions And Open Questions

 ### A. Assumptions 
The development of the application is based on the following assumptions:\
1.Restaurants are willing to register their business on the platform.\
2.Customers have access to a good internet.\
3.A trustworthy third party payment gateway should be united.<br>
4.Riders are available to fulfil customers orders.\
5.Customers would have valid and accurate delivery addresses.

### B. Open questions 
These are questions that must be answered before or during development.

|ID|Open questions|Why it matters|
|---|---|---|
|OP01|Would customers complains and refunds be attended to?|Determines customer support process.|
|OP02|How would customers make payment?|Determines the available payment option.|
|OP03|Would delivers be handled by trusted and skilled riders?|Determines smooth, fast and reliable deliveries.|
|OP04|Who sets and receives delivery charges?|Determines revenue model.|
|OP05|How would vendor verify that an order has been collected by the correct rider?|Determines accurate trackimg order.|
|OP06|What customers information is order necessary for a successful delivery?|Determines the authenicity of the customer upon delivery.|
|OP07|what would happen when a vendor rejects a customers order?|Determines work ethics.|

---

## Conclusion 
The proposed Food Delivery Application aims to simplify the process of ordering food and delivering food to students on campus by connecting various vendors, delivery riders and students on a centralized platform.

By incorporating the highlighted Functional Requirements and Non-Functional Requirements, the application will provide a secure, reliable and east going experince when ordering.

The initial developnment will dwell on core features which are;User Registeration, Shopping cart, Payment PLatforms, Vendor Listing, Food menu and delivery management.

**Main Goal:** To develop a reliable food delivery platform that improves customer convenience, eliminate long distance walks fo rordering of food and generate more revenue for the vendors.
