# Mobile Recharge Planner

## Overview

The Mobile Recharge Planner is a Python-based console application designed to manage and analyze mobile recharge plans efficiently. It offers a simple way to store, update, view, and analyze recharge information for multiple mobile numbers at one place.[1]

## Features

- Password-protected access to the application (default password: `admin123`).[1]
- Add a new recharge plan for any mobile number, including operator, plan name, validity, amount, and recharge date.[1]
- Update or delete existing recharge plans by mobile number.[1]
- View all saved recharge plans with details.[1]
- Calculate and display the total recharge amount recorded so far.[1]
- Calculate average plan cost from all entered recharges.[1]
- Show the number of plans grouped by operator.[1]
- Search recharge records either by mobile number or operator name.[1]

## Usage

1. Run the script in a Python environment (Python 3 recommended).[1]
2. When prompted, enter the application password (`admin123` by default) to gain access.[1]
3. Choose from the main menu:
   - Add, view, update, or delete recharge plans.
   - Analyze total and average recharge amounts.
   - See statistics by operator or search for specific records.[1]
4. Follow on-screen instructions for each operation.[1]

## Data Structure

- All recharge plans are stored as a dictionary with the mobile number as the key and related plan data as the value.[1]
- Each record tracks:
  - Mobile number
  - Operator name
  - Plan name
  - Validity (days)
  - Plan amount
  - Recharge date
  - History of recharge amounts for updates[1]

## Dependencies and Setup

- No external Python packages are required; the application uses only built-in modules such as `datetime`.[1]
- To run, simply execute the script using Python 3.[1]

## Author

- Yanshika Rana
- Enrollment Number: 2502140120

## License

This mini-project is for educational and demonstration purposes.
