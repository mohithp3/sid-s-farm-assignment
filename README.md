Objective
This SQL query calculates the total quantity of each product that needs to be transported by each vehicle within a specified date range. It provides a report of the aggregated product quantities for logistics planning.

Tables
Customers: Contains fields Customer_id and Route_id.
Routes: Contains fields Route_id and Vehicle_id.
Vehicles: Contains fields Vehicle_id, Parent_vehicle_id, and Parent_branch_id.
Orders: Contains fields Customer_id, Product_Name, Quantity, Order_status, and Delivery_date.
Constraints
Only include orders with the Order_status marked as 'confirmed'.
The date range for the orders (Delivery_date) will be provided.
