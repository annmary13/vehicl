# VEHICLE SERVICE MANAGEMENT
## FUNCTIONS
## Customer
- customer will signup and login into system
- customer can make request for service of their vehicle by providing details (vehicle number, model, problem description etc.)
- After Request approved by admin, customer can check cost, status of service
- customer can delete request (Enquiry) if customer change their mind or not approved by admin (ONLY PENDING REQUEST CAN BE DELETED )
- customer can check status of Request(Enquiry) that is Pending, Approved, Repairing, Repairing Done, Released
- customer can check invoice details or repaired vehicles
- customer can send feedback to admin
- customer can see/edit their profile
---
## Mechanic
- mechanic will apply for job by providing details like (skills, address, mobile etc.)
- Admin will hire(approve) mechanic account based on skill
- After account approval, mechanic can login into system
- mechanic can see how many work (vehicles to repair) is assigned to me
- mechanic can change status of service ('Repairing', 'Repairing Done') according to work progress
- mechanic can see salary and how many vehicles he/she have repaired so far
- mechanic can send feedback to admin
- mechanic can see/edit their profile
---
### Admin
- First admin will login ( for username/password run following command in cmd )
- Give username, email, password and your admin account will be created.
- After login , admin can see how many customer, mechanic, recent service orders on dashboard
- Admin can see/add/update/delete customers
- Admin can see each customer invoice (if two request made by same customer it will show total sum of both request)
- Admin can see/add/update/delete mechanics
- Admin can approve(hire) mechanics (requested by mechanic) based on their skills
- Admin can see/update mechanic salary
- Admin can see/update/delete request/enquiry for service sent by customer
- Admin can also make request for service (suppose customer directly reached to service center/office)
- Admin can approve request for service made by customer and assign to mechanic for repairing and will provide cost according to problem description
- Admin can see all service cost of request (both approved and pending)
- Admin can see feedbacks sent by customer/mechanic
---

## HOW TO RUN THIS PROJECT
- Enter following URL in Your Browser Installed On Your Pc
http://127.0.0.1:5500/home.html
## Disclaimer
This project is developed for demo purpose and it's not supposed to be used in real application.

## Feedback
Any suggestion and feedback is welcome. 
