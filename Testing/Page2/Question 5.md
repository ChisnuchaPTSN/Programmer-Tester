# 4. จากตาราง Customer ให้เขียน Query เพอืแสดงข้อมูล Used ทีมีค่ามากกว่า 500,000


```
SELECT 
    Customer.ID AS CustomerID, 
    Customer.Name, 
    Order.ID AS OrderID, 
    Order.Date, 
    Order.Amount 
FROM 
    Customer 
INNER JOIN 
    Order 
ON 
    Customer.ID = Order.CustomerID;

```
