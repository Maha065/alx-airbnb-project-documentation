# Airbnb Clone Backend - Data Flow Diagram (DFD)

This diagram illustrates how data flows between **users, processes, and databases** in the Airbnb Clone backend system.

## 📌 Key Components

### External Entities
- Guest
- Host
- Admin
- Payment Gateway
- Email Service

### Processes
1. User Management  
2. Property Listings Management  
3. Booking Management  
4. Payment Processing  
5. Reviews & Ratings  
6. Notifications  
7. Admin Dashboard  

### Data Stores
- Users DB  
- Properties DB  
- Bookings DB  
- Payments DB  
- Reviews DB  

## 📊 Data Flow Diagram
![Airbnb Clone DFD](./data-flow.png)

---

This DFD captures **inputs, processes, and outputs** for core backend operations like registration, bookings, payments, and notifications.
cd alx-airbnb-project-documentation
mkdir -p data-flow-diagram
mv data-flow.drawio data-flow-diagram/
mv data-flow.png data-flow-diagram/
mv README.md data-flow-diagram/

git add .
git commit -m "Add Airbnb Clone Backend Data Flow Diagram and documentation"
git push origin main

