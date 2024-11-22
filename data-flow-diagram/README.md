# Data Flow Diagram for Airbnb Clone Backend

## Objective
This repository contains a **Data Flow Diagram (DFD)** that visualizes how data flows through the core backend functionalities of the Airbnb Clone project. The DFD highlights key entities, processes, data inputs, and outputs, providing a clear understanding of the system’s architecture.

---

## Key Features Illustrated in the DFD
The DFD maps the data interactions between the following **core features**:

1. **User Authentication**  
   - **Data Input**: User details (email, password).  
   - **Processes**: Registration and login.  
   - **Output**: Verified user accounts stored in the **User Database**.

2. **Property Management**  
   - **Data Input**: Property details (title, description, location, price).  
   - **Processes**: Adding, updating, or deleting property listings.  
   - **Output**: Property data stored in the **Property Database**.

3. **Booking System**  
   - **Data Input**: Booking details (property ID, dates, guest info).  
   - **Processes**: Creating, updating, or canceling bookings.  
   - **Output**: Reservation details stored in the **Booking Database**.

4. **Payment Integration**  
   - **Data Input**: Payment details (transaction ID, amount).  
   - **Processes**: Secure payment processing via a payment gateway.  
   - **Output**: Payment confirmations stored in the **Payment Records**.

---

## Structure of the Repository

```plaintext
alx-airbnb-project-documentation/
│
├── data-flow-diagram/
│   └── data-flow.png
│   └── README.md
│
├── README.md
