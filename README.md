# Currency Converter Application
This application is a web-based currency converter that allows users to calculate the exchange rate between two selected currencies. It is designed with an intuitive interface and provides real-time conversion rates. Here's a detailed breakdown of its functionality:

#### Key Features:
1. **Currency Selection**:
   - Users can select "From" and "To" currencies from dropdown menus populated with currency codes.
   - The dropdowns are dynamically populated from a predefined list of currency codes (`Country_List`), with flags displayed for each selected currency.

2. **Real-Time Exchange Rates**:
   - The application fetches the latest exchange rates from the ExchangeRate API using the base currency selected by the user.
   - It calculates and displays the equivalent value in the target currency based on the input amount.

3. **Interactive Elements**:
   - Users can reverse the "From" and "To" currencies by clicking the reverse icon.
   - The application updates the flags and recalculates the exchange rate upon reversal.

4. **Automatic Updates**:
   - The application fetches and displays the exchange rate as soon as the page loads or when a new conversion is initiated.

5. **Error Handling**:
   - Displays meaningful messages if there are issues fetching the exchange rate, such as network errors or unavailable rates for the selected currencies.

#### How It Works:
1. **User Input**:
   - The user enters the amount to convert and selects the desired currencies.
2. **API Integration**:
   - The application sends a request to the ExchangeRate API to retrieve real-time conversion rates.
3. **Display Results**:
   - The result of the conversion is shown in a readable format, such as `1 USD = 0.75 GBP`.

#### Technologies Used:
- **HTML**: For structuring the interface.
- **CSS**: To style the application and enhance the user experience.
- **JavaScript**: To manage interactivity, API calls, and dynamic updates to the interface.
- **ExchangeRate API**: Provides real-time currency exchange data.

This application is suitable for individuals or businesses needing quick and reliable currency conversion.
