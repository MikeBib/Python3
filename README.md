Simply Customer Receipt 

#This is simple coding for a customer receipt which includes the description of each peice purchased, and the total cost with tax. 

#Catalog Items
lovely_loveseat_description = "Loveley Loveseat. Tufted polyester blend on wood. 32 inches high and 40 inches wide x 30 inches deep. Red or white."
lovely_loveseat_price = 254.00
stylish_settee_description = "Stylish Settee. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black."
stylish_settee_price = 180.50
luxurious_lamp_description = "Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade."
luxurious_lamp_price = 52.15
sales_tax = .088
customer_one_total = 0

#Customer One - List of Itemizations
customer_one_itemization = ""

#Customer Buys Loveseat
customer_one_total += lovely_loveseat_price
customer_one_itemization += lovely_loveseat_description

#Customer One Buys a Luxerious Lamp
customer_one_total += luxurious_lamp_price
customer_one_itemization += luxurious_lamp_description

#Customer One's Tax
customer_one_tax = customer_one_total * sales_tax

#Customer's Receipt
print("Customer One Items")
print(customer_one_itemization)
print("")
print("Total Price")
print(customer_one_total)
print("Total Tax")
print(customer_one_tax)
print("Final Charge")
print(customer_one_total + customer_one_tax)
