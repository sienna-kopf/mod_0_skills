## class Table

#### Attributes:
- number_of_seats (integer)
- taken (boolean)
- server (string)
- covering_material (string)
- diners_meal (hash, key: diner name, value: meal)

#### Methods:
- sit_down (tests to see if table is taken. If so, returns error message, if false, changes taken attribute to true.)
- change_server (modifies server attribute)
add_diner (modifies diners attribute by adding another diner to the end)
- shuffle_meals (modifies diners_meal attribute by shuffling which meal each diner gets)
- add_seat (modifies number_of_seats attribiute)
