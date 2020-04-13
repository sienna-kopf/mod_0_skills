## Check instance - Oliver's check for dinner at Olive Garden

#### Attributes:
- bill_total: 44.72 #$
- ordered_items {11.99: "Rigatoni with Chicken", 15.99: "Seafood Plate", 9.99: "Buttered Pasta", 6.75: "Tiramisu")
- type_of_payment: "Debit Card"
- number_of_items: 4
- enough_money: false

#### Methods:
can_pay
if enough_money = true
  enough_money = true
  puts "Thank you for paying your bill."
else
  puts "I'm sorry, you do not have enough money to pay. Please supplement with another payment method."

add_item
number_of_items += 1
bill_total += item.price
ordered_items = {11.99: "Rigatoni with Chicken", 15.99: "Seafood Plate", 9.99: "Buttered Pasta", 6.75: "Tiramisu", 6.75: "Chocolate Cake"}

different_form_of_payment
type_of_payment = "Cash"
puts "Your new form of payment is #{type_of_payment}"

calculate_tip
bill_total += bill_total * 0.20
puts "Your total plus tip is #{bill_total}."
