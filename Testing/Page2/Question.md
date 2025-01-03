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
def calculate(x):
  days = 7
  remaining_water = x

  for _ in range(days):
    used_water = remaining_water / 3
    remaining_water -= used_water

  return remaining_water

initial_water = 5832

result = calculate(initial_water)
print("ปริมาณน้ำที่เหลือในถังหลังจาก 7 วัน:", result, "ลิตร")

```

# Question 8

```python
rows = int(input("Enter number of rows: "))
for i in range(rows, 0, -1):
    print(" " * (rows - i) + "* " * i)

```

# Question 9



# Question 10



# Question 11

### 888 + 88 + 8 + 8 + 8


# Question 12

## ผลรวมของแต้มเป็น 10

### กรณีที่แต้มรวมเป็น 10
(4, 6)
(5, 5)
(6, 4)
### มี 3 กรณีจากทั้งหมด 6 x 6 = 30

## ผลต่างของแต้มเป็น 2

### กรณีที่ผลต่างเป็น 2
(4, 6)
(5, 5)
(6, 4)
### มี 8 กรณีจากทั้งหมด 6 x 6 = 30
