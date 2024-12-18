# Title :- Currency-Converter-Using-HTML-CSS-JS

Currency Converter
A simple and interactive Currency Converter web application that allows users to convert amounts between different currencies using real-time exchange rates. The application fetches the latest exchange rates from the ExchangeRate-API and provides the conversion result, displaying the flags of the respective currencies.

Features
Real-time Exchange Rates: Fetches live exchange rates from the ExchangeRate-API.
Currency Dropdowns: Allows users to select currencies for conversion, with flags showing the selected countries.
Amount Input: Users can input the amount they wish to convert.
Dynamic Results: Displays the converted amount dynamically when the user clicks the "Get Exchange Rate" button.
Responsive Design: The design is mobile-friendly and adapts to various screen sizes.
Technologies Used
HTML: The structure of the web page.
CSS: Styling for the web page.
JavaScript: To handle the logic of currency conversion and interaction with the ExchangeRate-API.
ExchangeRate-API: Provides the currency exchange rates.
FontAwesome: For icons used in the UI.
Setup Instructions
Clone the Repository

Clone the project to your local machine:

bash
Copy code
git clone https://github.com/yourusername/currency-converter.git
cd currency-converter
Get an API Key

To fetch exchange rates, you need an API key from ExchangeRate-API.
Go to ExchangeRate-API and sign up to get your API key.
Update the API Key

Open codes.js file and replace the placeholder API key (84429bef2d34fdcd28034bed) with your actual API key:
javascript
Copy code
const BASE_URL = "https://v6.exchangerate-api.com/v6/YOUR_API_KEY/latest";
Open the Project in Your Browser

Open the index.html file in your preferred browser.
The currency converter should now be ready to use.
File Structure
graphql
Copy code
/currency-converter
    ├── index.html         # The main HTML file containing the structure
    ├── style.css          # The CSS file for styling
    ├── codes.js           # JavaScript file handling currency conversion
    ├── app.js             # Additional JavaScript file (if needed for other logic)
    └── README.md          # This README file
How to Use
Select the "From" and "To" Currencies:

Choose the currency you want to convert from and to, using the dropdown menus.
Enter the Amount:

Type the amount you wish to convert in the input field.
Click "Get Exchange Rate":

Click the button to get the conversion result.
The result will be displayed below the button in the format: "1 USD = 80 INR".
Troubleshooting
Invalid Currency Code: If you get an "Invalid currency code" message, check if you have selected valid currencies from the dropdowns.
Error Fetching Exchange Rate: If there is a network issue, ensure your internet connection is stable and the API key is valid.
Contributing
Feel free to fork this project, submit issues, and create pull requests. Any contributions are welcome!

License
This project is open source and available under the MIT License.
