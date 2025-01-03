# Question 4

```
SELECT * 
FROM Customer 
WHERE Used > 500000;

```


# Question 5

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

# Question 6


# Question 7

```python
def calculate_water_left(initial_volume):
    for _ in range(7):
        initial_volume -= initial_volume / 3
    return initial_volume

# Example usage
remaining_water = calculate_water_left(5832)
print(f"น้ำที่เหลือในถัง: {remaining_water:.2f} ลิตร")

```

# Question 8

```python
rows = int(input("Enter number of rows: "))
for i in range(rows, 0, -1):
    print("* " * i)

```

# Question 9



# Question 10



# Question 11



# Question 12

 ผลรวมของแต้มเป็น 10
ลูกเต๋าแต่ละลูกมีแต้ม 1-6:

กรณีที่แต้มรวมเป็น 10:
(4, 6)
(5, 5)
(6, 4)
มี 3 กรณีจากทั้งหมด 
6
×
6
=
36
6×6=36
