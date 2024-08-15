# Customer-Receipts---Basic
creating a simple receipt with items; descriptions and a total (including VAT) in python
#Lovely Love Seats = furniture store name

lovely_loveseat_description = """
Lovely Loveseat.
Tufted polyester blend on wood.
32 inches high x 40 inches wide x 30 inches deep.
Red or white.
"""

#Lovely Loveseat Price Variable
lovely_loveseat_price = 254.00

# New furniture piece - Stylish Settee 
stylish_settee_description = """
Stylish Settee.
Faux leather on birch.
29.50 inches high x 54.75 inches wide x 28 inches deep.
Black.
"""

#Stylish Settee Price Variable
stylish_settee_price = 180.50

#New furniture piece - luxurious lamp
luxurious_lamp_description = """
Luxurious Lamp.
Glass and iron. 36 inches tall.
Brown with cream shade. 
"""

#luxurious lamp price variable
luxurious_lamp_price = 52.15

#company tax 
sales_tax = 0.088

#First customer 
customer_one_total = 0

#customer purchase list string
customer_one_itemization = ""

# customer one lovely loveseat purchase

customer_one_total += lovely_loveseat_price

#adding the description to customer one item list 
customer_one_itemization += lovely_loveseat_description

#adding the luxurious lamp to customer total
customer_one_total += luxurious_lamp_price

#adding luxurious lamp description to itemization
customer_one_itemization += luxurious_lamp_description

#calculating customer on tax

customer_one_tax = customer_one_total * sales_tax

#adding tax to customer one total
customer_one_total += customer_one_tax

#printing the receipt
print("Customer One Items:")
print(customer_one_itemization)
print("Customer One Total:")
print(customer_one_total)
