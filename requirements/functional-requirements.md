# Functional Requirements

## Overview

The functional requirements describe the capabilities that an improved cake order management solution should provide.

These requirements are derived from the identified business requirements, current process, pain points, root cause analysis, and stakeholder needs.

## Order Management

### FR-01: Create Customer Order

The system should allow the business owner to create a new customer order.

The order should include the relevant customer and cake details.

**Related Business Requirement:** BR-01, BR-02

---

### FR-02: Record Customer Details

The system should allow the owner to record customer information, including:

- Customer name
- Contact number

**Related Business Requirement:** BR-02

---

### FR-03: Record Cake Requirements

The system should allow the owner to record the customer's cake requirements, including:

- Cake design
- Flavour
- Size
- Other customization details

**Related Business Requirement:** BR-02

---

### FR-04: Record Required Date and Time

The system should allow the owner to record the required date and time for the order.

**Related Business Requirement:** BR-02, BR-04

---

### FR-05: Select Order Type

The system should allow the owner to specify whether the order is:

- Customer pickup
- Delivery

**Related Business Requirement:** BR-07

---

### FR-06: Record Delivery Details

When delivery is selected, the system should allow the owner to record the required delivery information, including:

- Delivery address
- Customer contact number
- Delivery date and time

**Related Business Requirement:** BR-07

---

## Payment Management

### FR-07: Record Deposit Payment

The system should allow the owner to record whether the required 50% deposit has been received.

The order should only be considered confirmed after the required deposit has been received.

**Related Business Requirement:** BR-06

---

### FR-08: Track Remaining Payment

The system should allow the owner to record the status of the remaining payment.

The payment status should indicate whether:

- The remaining payment is pending
- Full payment has been received

**Related Business Requirement:** BR-06

---

### FR-09: Prevent Completion Before Full Payment

The system should clearly indicate when the remaining payment is still pending before the cake is handed over to the customer.

**Related Business Requirement:** BR-06, BR-10

---

## Order Tracking

### FR-10: Display Upcoming Orders

The system should display confirmed upcoming orders based on their required dates.

The owner should be able to identify orders that are approaching their required date.

**Related Business Requirement:** BR-01, BR-04, BR-09

---

### FR-11: Display Order Details

The owner should be able to open an order and view its complete recorded information.

The information should include customer details, cake requirements, required date and time, order type, payment status, and order status.

**Related Business Requirement:** BR-02, BR-08

---

### FR-12: Search Orders

The system should allow the owner to search for an existing order using relevant customer or order information.

**Related Business Requirement:** BR-08

---

### FR-13: Track Order Status

The system should allow the owner to track the progress of an order.

Possible order statuses should include:

- Pending Confirmation
- Confirmed
- Preparing
- Ready
- Completed
- Cancelled

**Related Business Requirement:** BR-10

---

## Preparation Management

### FR-14: Identify Orders Requiring Preparation

The system should allow the owner to identify orders that require preparation based on their required date and time.

**Related Business Requirement:** BR-05

---

### FR-15: Record Preparation Status

The system should allow the owner to update the preparation status of an order.

The status should indicate whether preparation is:

- Not Started
- In Progress
- Completed

**Related Business Requirement:** BR-05, BR-10

---

## Pickup and Delivery Management

### FR-16: Identify Pickup Orders

The system should clearly identify orders that will be collected by the customer.

**Related Business Requirement:** BR-07

---

### FR-17: Identify Delivery Orders

The system should clearly identify orders that require delivery.

**Related Business Requirement:** BR-07

---

### FR-18: Record Delivery Arrangement

The system should allow the owner to record when a third-party delivery service such as PickMe or Uber has been arranged for an order.

**Related Business Requirement:** BR-07, BR-10

---

## Order Completion

### FR-19: Mark Order as Completed

The system should allow the owner to mark an order as completed after the cake has been handed over to the customer or successfully delivered.

**Related Business Requirement:** BR-10

---

### FR-20: Confirm Full Payment Before Completion

The system should show the payment status when the owner is completing an order so that the owner can verify that the remaining payment has been received.

**Related Business Requirement:** BR-06, BR-10

---

## Requirement Traceability

| Functional Requirement | Related Business Requirement |
|---|---|
| FR-01 | BR-01, BR-02 |
| FR-02 | BR-02 |
| FR-03 | BR-02 |
| FR-04 | BR-02, BR-04 |
| FR-05 | BR-07 |
| FR-06 | BR-07 |
| FR-07 | BR-06 |
| FR-08 | BR-06 |
| FR-09 | BR-06, BR-10 |
| FR-10 | BR-01, BR-04, BR-09 |
| FR-11 | BR-02, BR-08 |
| FR-12 | BR-08 |
| FR-13 | BR-10 |
| FR-14 | BR-05 |
| FR-15 | BR-05, BR-10 |
| FR-16 | BR-07 |
| FR-17 | BR-07 |
| FR-18 | BR-07, BR-10 |
| FR-19 | BR-10 |
| FR-20 | BR-06, BR-10 |

## Key Observation

The functional requirements are intended to address the weaknesses identified in the current process.

In particular, the requirements reduce the need to rely on WhatsApp conversations, pinned chats, and manual calendar entries as separate tracking mechanisms.

The proposed functionality provides a structured way to record, find, monitor, prepare, and complete customer orders.