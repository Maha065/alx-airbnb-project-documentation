# Airbnb Clone Backend - Use Case Diagram

This diagram illustrates the interactions between different actors and the **Airbnb Clone Backend system**.

## 📌 Actors
- **Guest**: Registers, searches, books, cancels bookings, leaves reviews.  
- **Host**: Manages listings, cancels bookings, responds to reviews.  
- **Admin**: Monitors users, listings, and payments.  
- **Payment Gateway**: Handles transactions and payouts.  
- **Email Service**: Sends booking confirmations, cancellations, and notifications.  

## 📊 Use Case Diagram
![Airbnb Use Case Diagram](./airbnb-use-case.png)

## ✅ Key Use Cases
- Register/Login & Manage Profile  
- Add/Edit Property Listings  
- Search Properties  
- Book/Cancel Property  
- Process Payments & Payouts  
- Leave/Respond to Reviews  
- Send Notifications  
- Admin Dashboard (manage users, listings, payments)  
cd alx-airbnb-project-documentation
mkdir -p use-case-diagram
mv airbnb-use-case.drawio use-case-diagram/
mv airbnb-use-case.png use-case-diagram/
mv README.md use-case-diagram/

git add .
git commit -m "Add Airbnb Clone Backend Use Case diagram and documentation"
git push origin main
