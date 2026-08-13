# Root Cause Analysis

## Problem Being Investigated

A customer placed a cake order approximately one month before the required date. However, the order was not added to the owner's calendar and the WhatsApp conversation was not pinned.

The order was only discovered when the customer asked about the cake one day before the required date.

The purpose of this analysis is to identify why the order was not properly recorded and tracked.

## 5 Whys Analysis

### Why 1: Why was the order almost missed?

The order was not identified as an upcoming order until one day before the required date.

### Why 2: Why was the order not identified as an upcoming order?

The order had not been added to the owner's calendar and the WhatsApp conversation had not been pinned.

### Why 3: Why were the calendar and WhatsApp chat not updated?

The process depends on the owner manually performing these actions after confirming an order.

### Why 4: Why does the process depend on manual actions?

The current order management process uses separate tools for communication and order tracking. WhatsApp is used for customer communication, while the calendar is used to track upcoming dates.

There is no single process step that ensures the confirmed order is recorded in the tracking system.

### Why 5: Why is there no reliable step ensuring that every confirmed order is tracked?

The current process does not have a structured order tracking mechanism or a control that verifies whether every confirmed order has been recorded.

## Root Cause

The main root cause identified is the **reliance on manual order tracking across separate tools without a reliable control to ensure that every confirmed order is recorded and monitored**.

The issue is therefore not simply that the owner forgot to add one order to the calendar. The larger process weakness is that successful order tracking depends on the owner remembering and completing multiple manual actions.

## Contributing Factors

Several factors contribute to the risk of an order being missed:

### 1. Multiple Tracking Locations

Order information is distributed between WhatsApp, pinned chats, and the calendar.

### 2. Manual Data Entry

The owner must manually transfer order information into the calendar.

### 3. Dependence on Memory

The process relies on the owner remembering to update the tracking methods after an order is confirmed.

### 4. Lack of a Tracking Control

There is currently no formal step that verifies whether every confirmed order has been successfully recorded.

### 5. Long Lead Time Between Order and Required Date

Customers may place orders several weeks before the required date. This increases the possibility that an order can become less visible if it is not properly recorded.

## Root Cause Summary

| Category | Finding |
|---|---|
| Immediate Issue | Order was not added to the calendar |
| Related Issue | WhatsApp conversation was not pinned |
| Process Issue | Order tracking relies on manual actions |
| System Issue | Information is distributed across separate tools |
| Control Gap | No reliable verification that every confirmed order is recorded |
| Root Cause | Manual and fragmented order tracking process |

## Key Finding

The analysis indicates that the missed-order incident was caused by a weakness in the order tracking process rather than simply an individual mistake.

The existing process relies heavily on the owner's memory and manual actions. A more reliable process should reduce this dependency and provide a clear method for ensuring that every confirmed order is recorded, visible, and monitored until completion.