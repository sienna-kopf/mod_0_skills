## class Check

#### Attributes:
- bill_total (float)
- ordered_items (hash, key: price, value: item name)
- type_of_payment (string)
- number_of_items (integer)
- enough_money (boolean)

#### Methods:
- can_pay (tests to see if enough_money = true, if so returns true. If false, returns false and error message)
- add_item (modifies number_of_items attribute, bill_total attribute, and adds a key and item pair to the ordered_items hash)
- different_form_of_payment (modifies type_of_payment Attribute)
- calculate_tip (modifies bill_total using calculation)
