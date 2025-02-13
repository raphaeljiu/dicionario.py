products = {}

for i in range(5):
    product_name = input(f"Enter the name of product {i+1}: ")
    product_price = float(input(f"Enter the price of {product_name}: "))
    products[product_name] = product_price

total_value = sum(products.values())

print(f"\nThe total purchase value is: ${total_value:.2f}")
