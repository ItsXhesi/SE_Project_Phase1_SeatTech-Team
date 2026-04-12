System Requirements

1. Chosen Development Model

Agile

The selection follows Agile because it provides the opportunity for change and improvement. Since user requirements (students and employees) can be dynamic, Agile allows for frequent change and feature implementation progressively.

2. User Requirements

a. Stakeholders (WHO is involved)

1.	Students (End Users)

- Use the system to order food 
- Want fast service and no waiting lines 
- Students should be able to view food availability in real time.

2.	Cafeteria Staff
   
- Prepare and handle orders 
- Want a structured and manageable workload 
- Staff should be able to view and manage incoming orders.
  
Cafeteria Manager (Admin) 

- Manages menu, availability, and reports 
- Wants control in order for efficiency 
- Staff must update order status (preparing, ready).
  
3.	System Developers
   
- Build and maintain the system 
- Implementing performance and reliability

User Stories (WHAT they need and WHY)

Students

1.	As a student, I want to see the daily menu and make a choice as to what I should order.
2.	As a student, I want to pre-order food so that I can avoid waiting in line. 
3.	As a student, I want to see food availability so that I don’t order unavailable items. 
4.	As a student, I want to reserve a pickup time so that I can collect food quickly. 
5.	As a student, I want to receive notifications so that I know when my order is ready.
   
Cafeteria Staff

1.	As staff, I want to see incoming orders so that I can prepare them on time. 
2.	As staff, I want orders organized by time so that work is efficient. 
3.	As staff, I want to update order status so that students are informed. 
4.	As staff, I want to manage food availability so that the system stays accurate.
   
Admin (Manager)

1.	As an admin, I want to update the menu so that students see correct options. 
2.	As an admin, I want to manage food stock so that shortages are avoided. 
3.	As an admin, I want reports of orders so that I can analyze demand. 
4.	As an admin, I want to manage users so that the system stays secure.

Functional Requirements (what the system must do)

1.	The system should allow registration and log in for the user.
2.	The system should allow user singup. 
3.	The system should show the daily menu. 
4.	The system should display food prices. 
5.	The system should display real time food. 
7.	The system should allow students to select food items. 
8.	The system should allow students to add items to cart. 
9.	The system should allow students to place orders when applicable.
10.	The system should allow users to select pickup time slots. 
11.	The system should prevent double booking of time slots. 
12.	The system should generate order confirmation. 
13.	The system should send notifications to users. 
14.	The system should allow order cancellation. 
15.	The system should allow order modification before confirmation. 
16.	The system should allow staff to view all orders. 
17.	The system should allow staff to update order status. 
18.	The system should allow admin to add menu items. 
19.	The system should allow admin to update menu items. 
20.	The system should allow admin to delete menu items. 
21.	The system should allow admin to manage stock levels. 
22.	The system should generate daily reports. 
23.	The system should store order history. 
24.	The system should support multiple users. 
25.	The system should provide search functionality for menu items.
26. The system should display order status in real time.

b. Acceptance Criteria (When we know it WORKS correctly)

1. User Login

•	User enters correct email/password 

•	System confirms credentials 

•	User redirected to dashboard 

•	Error shown if invalid

2. Pre-order Food
   
•	User clicks on items 

•	Items previously been saved to cart 

•	Order verified successfully 

•	Confirmation message displayed 

3. Real-Time Availability

•	System updates availability instantly 

•	Out-of-stock items cannot be selected 

•	Users see updated data 

4. Pickup Time Slot

•	User selects available slot 

•	Slot is reserved 

•	System prevents double booking 

•	Confirmation displayed

5. Order Management (Staff)

•	Staff can view orders 

•	Staff updates status 

•	Status is reflected to the user 


Non-Functional Requirements (How well the system should work)

1.	The system should load pages rapidly. 
2.	The system should support multiple users efficiently. 
3.	The system should be easy to use. 
4.	The system should have a simple interface. 
5.	The system should be available 24/7. 
6.	The system should ensure data security. 
7.	The system should encrypt user passwords. 
8.	The system should prevent unauthorized access. 
9.	The system should be scalable. 
10.	The system should be reliable with minimal downtime. 
11.	The system should recover from failures quickly. 
12.	The system should support mobile and desktop devices. 
13.	The system should have fast response time. 
14.	The system should provide real-time updates. 
15.	The system should maintain data integrity. 
16.	The system should support backup and recovery. 
17.	The system should have clear error messages. 
18.	The system should be compatible with major browsers. 
19.	The system should be maintainable. 
20.	The system should support future upgrades. 
21.	The system should log system activities. 
22.	The system should protect user privacy. 
23.	The system should have minimal bugs. 
24.	The system should ensure consistent performance. 
25.	The system should handle peak load times. 

b. Acceptance Criteria


1. Performance

•	Pages load under 2 seconds 

•	Orders processed under 5 seconds 

•	No lag during peak time 


2. Usability
   
•	Interface is simple 

•	Users complete order in < 1 minute 

•	Navigation is clear 


3. Security
   
•	Passwords encrypted 

•	Login required 

•	Unauthorized access blocked 


4. Reliability
   
•	System uptime ≥ 99% 

•	System handles errors properly 

•	No data loss 


5. Scalability

•	System supports many users 

•	Performance remains stable 

•	Can expand easily 


Application Specifications (How the system is built technically)

a. Architecture


Provide an overview of the system architecture, including components and interactions.

The system follows a three-tier architecture:

•	Frontend: User interface (students & staff interact here) 

•	Backend: Processes logic and handles requests 

•	Database: Stores users, orders, and menu data


b. Database Model

Describe the database structure: tables, relationships, and constraints.
Tables include:

•	Users (id, name, email, password, role) 

•	Menu (id, item_name, price, availability) 

•	Orders (id, user_id, status, time_slot) 

•	Order_Items (order_id, menu_id, quantity) 


Relationships:

•	One user → many orders 

•	One order → many items 


c. Technologies Used

•	Frontend: HTTML (simple UI) 

•	Backend: Python (fast and scalable) 

•	Database: MySQL (structured data) 

•	Platform: Runs on web (browser, Windows compatible) 


d. User Interface Design

•	Login/Register page 

•	Dashboard with menu 

•	Order page with item selection 

•	Pickup time selection 

•	Order status page 


e. Security Measures

•	User authentication (login system) 

•	Password encryption 

•	Role-based access (admin/staff/student) 

•	Optional two-factor authentication 

•	Data protection against unauthorized access 


