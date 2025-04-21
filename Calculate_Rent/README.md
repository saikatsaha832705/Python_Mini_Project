### This Python script, `calculate_rent.py`, is designed to help calculate the individual share of rent and common expenses for people living together in a shared accommodation. It takes several inputs related to the total expenses and the number of occupants and then provides a breakdown of these costs per person.

#### Parameters:

- total_rent (int): The total monthly rent for the entire room or flat. This value should be in Indian Rupees (INR).
- food_cost (int): The total cost incurred on food items ordered for snacking or shared consumption during the period (typically monthly). This value should be in INR.
- electricity_units (int): The total number of electricity units consumed during the billing cycle.
- charge_per_unit (int): The cost per unit of electricity as charged by the electricity provider. This value should be in INR per unit.
- num_persons (int): The total number of individuals residing in the room or flat who will be sharing these expenses. This must be a positive integer.

#### Return Value:

*A dictionary containing the following key-value pairs representing the individual breakdown of expenses:*
- 'rent_per_person' (int): The amount each person has to pay towards the rent.
- 'food_per_person' (int): The amount each person has to contribute towards the cost of shared snacks.
- 'electricity_cost' (int): The total cost of electricity consumed.
- 'electricity_per_person' (int): The amount each person has to contribute towards the electricity bill.
- 'total_per_person' (int): The sum of the individual's share of rent, food, and electricity, representing the total expense per person. If the num_persons is zero or negative, the function returns an error message: "Error: Number of persons must be greater than zero."

#### How to Use:
**1. Save the Code:** Save the provided Python code as a .py file (e.g., rent_calculator.py).<br>
**2. Run from Terminal:** Open a terminal or command prompt, navigate to the directory where you saved the file, and run the script using the command: python rent_calculator.py<br>
**3. Enter Inputs:** The script will prompt you to enter the following information one by one:<br>
- Total rent
- Total cost of snacks
- Total electricity units consumed
- Charge per electricity unit
- Number of people living in the room/flat

**4. View Results:** After you provide all the inputs, the script will calculate and display the individual share of rent, food cost, total electricity cost, individual electricity cost, and the total expense per person.
  ***
