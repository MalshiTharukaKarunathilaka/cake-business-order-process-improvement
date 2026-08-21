# User Stories and Acceptance Criteria

## Overview

The user stories translate the functional requirements into user-focused requirements that describe what the business owner needs to accomplish and why.

The stories are written from the perspective of the cake business owner because the owner is the primary user of the proposed order management process.

---

## US-01: Create a Customer Order

**As a** cake business owner,  
**I want to** record a new customer's order details,  
**so that** I can keep the order information organized and easily accessible.

**Related Requirements:** FR-01, FR-02, FR-03, FR-04

### Acceptance Criteria

- The owner can create a new order.
- The owner can enter the customer's name and contact number.
- The owner can enter the cake design and flavour.
- The owner can enter the cake size.
- The owner can enter the required date and time.
- The order cannot be confirmed without the required order information.

---

## US-02: Record Order Type

**As a** cake business owner,  
**I want to** record whether an order is for pickup or delivery,  
**so that** I know how the completed cake will be handed over to the customer.

**Related Requirements:** FR-05, FR-06

### Acceptance Criteria

- The owner can select pickup or delivery.
- If pickup is selected, the order is identified as a pickup order.
- If delivery is selected, the owner can enter the delivery address.
- The customer's contact number is available for delivery orders.

---

## US-03: Confirm an Order With a Deposit

**As a** cake business owner,  
**I want to** record the customer's 50% deposit,  
**so that** I can identify which orders have been confirmed.

**Related Requirements:** FR-07

### Acceptance Criteria

- The owner can record the deposit payment.
- The order shows whether the deposit has been received.
- An order with no deposit is shown as pending confirmation.
- An order with the required deposit is shown as confirmed.

---

## US-04: Track Remaining Payment

**As a** cake business owner,  
**I want to** track the remaining payment,  
**so that** I can confirm that the customer has paid the full amount before receiving the cake.

**Related Requirements:** FR-08, FR-09

### Acceptance Criteria

- The owner can see the current payment status.
- The remaining payment is shown as pending until received.
- The owner can record when the remaining payment is received.
- The order shows full payment completed after the remaining payment is recorded.

---

## US-05: View Upcoming Orders

**As a** cake business owner,  
**I want to** see upcoming confirmed orders,  
**so that** I can prepare cakes before their required dates.

**Related Requirements:** FR-10, FR-14

### Acceptance Criteria

- The owner can view upcoming orders.
- Orders are displayed with their required dates.
- The required time is visible.
- The owner can identify which orders are approaching.
- Completed orders are not shown as upcoming orders.

---

## US-06: View Complete Order Details

**As a** cake business owner,  
**I want to** view all information about an order in one place,  
**so that** I do not have to search through old WhatsApp conversations.

**Related Requirements:** FR-11

### Acceptance Criteria

- The owner can open an existing order.
- Customer details are displayed.
- Cake requirements are displayed.
- Required date and time are displayed.
- Payment status is displayed.
- Pickup or delivery information is displayed.
- Order status is displayed.

---

## US-07: Search for an Existing Order

**As a** cake business owner,  
**I want to** search for an existing order,  
**so that** I can quickly find an order when a customer contacts me.

**Related Requirements:** FR-12

### Acceptance Criteria

- The owner can search for an order.
- The owner can use customer information to find an order.
- Matching orders are displayed.
- The owner can open the required order from the search results.

---

## US-08: Track Order Preparation

**As a** cake business owner,  
**I want to** update the preparation status of an order,  
**so that** I know which cakes still need to be prepared.

**Related Requirements:** FR-14, FR-15

### Acceptance Criteria

- The owner can see whether preparation has started.
- The owner can mark preparation as in progress.
- The owner can mark preparation as completed.
- The current preparation status is visible on the order.

---

## US-09: Arrange Delivery

**As a** cake business owner,  
**I want to** record when a third-party delivery service has been arranged,  
**so that** I can keep track of the delivery stage of the order.

**Related Requirements:** FR-17, FR-18

### Acceptance Criteria

- The owner can identify an order as a delivery order.
- The delivery address is available.
- The owner can record that a delivery has been arranged.
- The delivery stage can be identified before the order is completed.

---

## US-10: Complete an Order

**As a** cake business owner,  
**I want to** mark an order as completed after pickup or delivery,  
**so that** I can distinguish completed orders from upcoming orders.

**Related Requirements:** FR-19, FR-20

### Acceptance Criteria

- The owner can mark an order as completed.
- The order shows its completed status.
- The payment status is visible before completion.
- The completed order is no longer treated as an upcoming order.

---

# User Story Summary

| ID | User Story | Priority |
|---|---|---|
| US-01 | Create a customer order | High |
| US-02 | Record order type | High |
| US-03 | Confirm an order with a deposit | High |
| US-04 | Track remaining payment | High |
| US-05 | View upcoming orders | High |
| US-06 | View complete order details | High |
| US-07 | Search for an existing order | High |
| US-08 | Track order preparation | High |
| US-09 | Arrange delivery | Medium |
| US-10 | Complete an order | High |

# Relationship to the Current Process

The user stories are intended to address the main weaknesses identified in the current process.

In the existing process, important order information may remain inside WhatsApp conversations while the owner separately relies on a calendar and pinned chats to remember upcoming orders.

The proposed requirements provide a more structured approach where order information, payment status, preparation status, and pickup or delivery details can be accessed together.

The purpose is not simply to replace WhatsApp, but to reduce the risk created by relying on multiple manual tracking methods.