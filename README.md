# Tax Calculator App in Flask

For details, please see SETaP on Moodle, TB2, w2. 

## Setup

1. Install Python 3.12.6
2. Install Flask 3.0.0
3. Install requirements.txt

## Run

1. Run app.py
2. Open http://localhost:5000

### TODO

#### Requirements

> Tax is paid on all income, including (but not limited to):

> Money earned from employment

> Interest on savings

> Bonuses you get from employment


R1: <s>Calculate tax on employment income as 20% of the total income.</s>

R2: <s>An allowance of £1000 is applied on all interest from savings. Calculate tax on all other interest earnings at a rate of 15%.</s>

R3: Tax on employment bonuses is calculated depending on the level of income, with a 20% rate on bonuses for all income lower than £25k, 40% for all income in (£25k, 50k), and 45% for all income higher than £50k. Calculate the tax on employment bonuses.


#### Implementation

> 1. Fork the repository TaxCalculator. You will use this as a template for building the app.

> 2. Open the TaxCalculator in Visual Studio Code. These files should be included:

> index.html - frontend, incorporating the html, css, and js components

> app.py - backend, defining the python components

> requirements.txt - config file used for installing flask

> 3. Install Flask.

> On Mac: pip3 install –r requirements

> On Windows: pip install –r requirements.txt

> 4. Run the app.

> On Mac: python3 app.py

> On Windows: python app.py

> In a separate browser, load the URL the app is running on. This is usually htttp://127.0.0.1:5000

> 5. The app is currently implementing R1 and R2. Please implement R3.

> Make sure you:

> q Allow the users to input a third type of income, bonusIncome

> q Create a space on the template page where you will display the result, taxOnBonus

> q Extract the dom fragment including the bonusIncome and its respective result

> q Extract the value of the bonusIncome from the dom fragment

> q Post the bonusIncome together with your api request

> q Change the python method to also check the validity of the bonusIncome and calculate taxOnBonus

> q Wrap the taxOnBonus (and the corresponding errors) into json objects and return them

> q Unpack the json objects on the JS side

> q Display the taxOnBonus in the GUI