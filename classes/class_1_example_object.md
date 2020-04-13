## Table instance - Hannah's table at Olive Garden

#### Attributes:
- number_of_seats: 5
- taken: false
- server: "Elliot"
- covering_material: "Glass"
- diners_meal: {"Hannah": "Pesto with Shrimp", "Mark": "Eggplant Parmesan", "Lucy": "Minestrone Soup"}

#### Methods:
sit_down
if taken = false
  taken = true
  puts "Here is your table!"
else
  puts "I'm sorry, but that table is taken."

change_server
server = "Craig"
puts "Your new server is #{server}."

add_diner
diners_meal.store(:"Carlo", "Italian Sausage sandwich")


shuffle_meals
diners_meal = {"Hannah": "Eggplant Parmesan", "Mark": "Pesto with Shrimp", "Lucy": "Minestrone Soup"}

add_seat
number_of_seats += 1
puts "This table now has #{number_of_seats} seats."
