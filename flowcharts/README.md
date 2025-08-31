# Flowcharts - Airbnb Clone Backend

## 🎯 Objective
This directory contains the flowchart for one of the **core backend processes** of the Airbnb Clone project. Flowcharts are used to represent step-by-step workflows of system operations, making it easier to understand the logic and data flow within the backend.

---

## 🏡 Selected Process: Property Booking
The flowchart provided here represents the **Property Booking workflow**, which is a critical feature of the Airbnb system. It illustrates how a guest interacts with the system to successfully book a property.

---

## 🔑 Workflow Steps
1. **Start** – The booking process begins when the guest selects a property.
2. **Property Selection** – The system receives the guest’s selected property.
3. **Check Availability** – The system validates whether the property is available for the selected dates.
   - If **not available**, the process ends with a "Not Available" message.
   - If **available**, the process continues.
4. **Enter Booking Details** – The guest provides stay details (dates, number of guests, etc.).
5. **Calculate Total Cost** – The system computes the total cost of the stay.
6. **Proceed to Payment** – The guest initiates payment.
7. **Payment Gateway Validation** – The system checks if payment is successful.
   - If **payment fails**, the user is prompted to retry.
   - If **payment succeeds**, the booking is confirmed.
8. **Confirm Booking & Update DB** – The booking is stored in the system database.
9. **Send Confirmation Email** – A booking confirmation is sent to the guest.
10. **End** – The process ends after confirmation.

---

## 📊 File Contents
- `data-flow-diagram.png` → Flowchart of the Property Booking process (exported from Draw.io)

---

## ✅ Key Benefits of This Flow
- Ensures **no double bookings** by validating availability.
- Integrates with **payment systems** for secure transactions.
- Provides a **smooth guest experience** with confirmations and notifications.
- Keeps data **consistent** by updating the database after successful booking.

---

📌 This flowchart forms the basis for **backend logic implementation** in later stages of the Airbnb Clone project.
