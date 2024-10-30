# GitHub-Final-Project

# This function calculates simple interest
interest=calculate_simple_interest(principal, rate, time)

# Calculate the total amount after interest is applied
total_amount=$(echo "$principal + $interest" | bc)

read -p "Enter principal amount: " principal
read -p "Enter rate of interest: " rate
read -p "Enter time in years: " time

## Running the Script
To run the simple interest calculation script, use the following command:
```bash
bash simple-interest.sh
