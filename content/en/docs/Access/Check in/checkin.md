
---
title: "Check in"
linkTitle: "Check in"
date: 2020-11-12
weight: 20
description: >
  Note: This content is currently in draft status.
---

The Check in app allows you to process items a patron returns to the library, items requested by a patron, or In process items. You can also use the Check in app to record in-house usage.

## Checking in an item

Once a patron returns an item, check it in to remove it from the patron’s account and charge any applicable fees/fines. If the item is checked in at its effective location and no patrons have requested it, then it is marked as available.

To check in an item, either scan the barcode of the item, or enter the barcode and click **Enter**. The item appears in the Scanned Items table and its status changes. Fees/fines owed are noted in the Time returned column, if applicable.

## Checking in an item on route to another service point    

There are two scenarios in which an item may need to be routed to another service point: a patron returns an item and the service point used at check in is not assigned to its effective location or a patron requests an item to be picked up at a different service point.

1. Either scan the barcode of the item, or enter the barcode and click **Enter**. If the item needs to be sent to another location, an **In transit** dialog appears noting the item is in transit and needs to be routed to a different service point.
2. Optional: If you do not want to print a routing slip, clear the **Print slip** checkbox.
3. Click **Close** to exit and print a routing slip, if selected. The item appears in the Scanned Items table and its status changes to In transit.

## Checking in an item with a request (hold shelf fulfilment)

When a patron requests an item, checking the item in at its requested pickup service point triggers the hold.

1. Either scan the barcode of the item, or enter the barcode and click **Enter**. An **Awaiting pickup for a request** dialog appears noting the item is awaiting pickup and lists its pickup service point.
2. Optional. If you do not want to print a hold slip, clear the **Print slip** checkbox.
3. Click **Close** to exit and print a hold slip, if selected. The item appears in the Scanned Items table and its status changes to Awaiting pickup. If configured, a pickup notice is sent to the patron once the check in session ends.

## Checking in an item with a request (delivery fulfilment)

Delivery requests are not treated any differently than items being routed to the hold shelf. The delivery request is triggered once the item is checked in at any location. See [Processing delivery requests]({{< ref "/requests.md#processing-delivery-requests" >}}) for more information.

1. Either scan the barcode of the item, or enter the barcode and click **Enter**. 
2. Optional: In the **Route for delivery request** dialog, if you do not want to print a hold slip, clear the **Print slip** checkbox.
3. To check out the item to the patron, click **Close and check out**. The check out window appears and the item is automatically checked out to the patron.
4. To leave the check out window, click **End Session**.

## Checking in and backdating an item

You may need to backdate a returned item if your library was closed on the date the patron returned the item and you do not want to have any fees/fines charged to the patron’s account.

For example, if your library was closed because of an emergency, you can mark all items returned the day your library was closed with the previous day’s date so that fees/fines will not accrue on patrons’ accounts.

1. Click the **pencil icon** under Process as or Time returned.
2. Change the date and /or time.
3. Either scan the barcode of the item, or enter the barcode and click **Enter**.  The item appears in the Scanned items table and the backdated time is listed in the Time returned column. To view the actual check in time, click the **information icon** in the Time returned column.

## Recording in-house use of an item

If you find an available item (not on loan) in the library away from its shelving location, you can check it in to mark the item as used. For example, you may want to use this setting for items in your reference collection or items on reserve.

Items that can be recorded in this way are available, have no open requests, and are checked in at a service point assigned to its effective location. 

To mark an item as used, either scan the barcode of the item, or enter the barcode and click **Enter**.  A house icon appears in the In-house use column to indicate the statistic has been recorded.

## Ending a check in session

Once you are done checking in items, you can end your check in session manually. To end your session and clear the Scanned Items table, click **End session**. Once you end the session, any applicable notices will be sent out to patrons.

By default, the Check in session is configured to end automatically after a 3 minute period of inactivity. You can turn this setting off or edit the number of minutes of inactivity the session will end after in the Settings app.