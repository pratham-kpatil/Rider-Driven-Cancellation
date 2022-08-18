# Rider-Driven-Cancellation
Given the order and rider details, create a model to predict the cancellation of the order before it is cancelled by the rider.
### Dataset Description
Columns ->  
order_id : unique id for each order  
order_time: time of the creation of order by the client  
order_date : date of the order  
allot_time: time of allocation of order to the rider  
accept_time: time of acceptance of the order by the rider    
pickup_time: time of pickup of the order  
delivered_time: time of delivery of the order  
cancelled_time: time of cancellation of order  
cancelled: whether the order was cancelled  
rider_id: unique id for each rider  
first_mile_distance: road distance from rider’s location to the pickup location
last_mile_distance: road distance from pickup location to the delivery location
allotted_orders: total number of orders allotted to the rider in the 30 days before (not including) order_date
delivered_orders: total number of orders delivered by the rider in the 30 days before (not including) order_date
undelivered_orders: total number of orders allotted to but not delivered by the rider (i.e. cancelled) in the 30 days before (not including) order_date
lifetime_order_count: total number of orders delivered by the rider at any time before order_date
reassigned_order: whether the order was reassigned to this rider
reassignment_method: if the order was reassigned, whether the reassignment was done manually (by the ops team) or automatically
reassignment_reason: a more detailed reason for the reassignment
session_time: total time the rider had been online on order_date before order_time

