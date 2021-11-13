#Welcome customer
print("Welcome to Python Shop")
#Get user input
name=input("Please enter your name:")
item=input("Please enter what you want to buy:")
color=input("Color:")
price=float(input("Price:"))
quantity=float(input("Quantity:"))
#process data
total_price = price * quantity
#Output receipt
print()
print("Your receipt:\n")
print("Name:"+name.title())
print("Perchased item:"+color.capitalize()+" "+item.lower())
print("price:"+str(price))
print("Quantity:"+str(quantity))
print("Total price:"+str(total_price))
