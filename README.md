# Currency_Exchange
Electron.js Desktop Application

This file contain html, java script and css codes used to create a desktop application using Electron.js 
## Features

- Dropdowns for selecting 'From' and 'To' currencies.
- Input for the amount and a button to convert.
- Display of the converted currency value.

## API

The application uses the ExchangeRate-API to fetch currency rates. You will need to sign up for an API key at [ExchangeRate-API](https://www.exchangerate-api.com/) and replace the API key in the code.

## Installation

Clone the repository: https://github.com/Imharsh08/Currency_Exchange.git
and then Install the dependencies: **npm install**

Replace the API key:
Open the **main.js** file.
Replace **'API_KEY'** with your actual API key from ExchangeRate-API.

Run the application: **npx electron.js**

**Usage**
1.Select the 'From' currency from the dropdown.
2.Select the 'To' currency from the dropdown.
3.Enter the amount to convert in the input field.
4.Click the 'Convert' button.
The converted currency value will be displayed.
![Screenshot (224)](https://github.com/Imharsh08/Currency_Exchange/assets/122665995/372fb09e-8bc2-45af-8b89-47cb213e3e21)
