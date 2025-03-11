# Currency Converter

A Python-based Currency Converter application with a graphical user interface (GUI) built using Tkinter. It fetches real-time exchange rates using the ExchangeRate-API and also provides a graphical representation of exchange rates using Matplotlib.

## Features
- Convert currency based on real-time exchange rates.
- Supports multiple currencies, fetched dynamically.
- Displays a graphical representation of exchange rates.
- User-friendly GUI with a modern design.

## Technologies Used
- **Python**
- **Tkinter** (for GUI)
- **Requests** (for API calls)
- **Matplotlib** (for data visualization)

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/CurrencyConverter.git
   cd CurrencyConverter
   ```
2. Install required dependencies:
   ```sh
   pip install requests matplotlib
   ```

## Usage
Run the script:
```sh
python currency_converter.py
```

### How to Use
1. Select a **Base Currency** from the dropdown.
2. Select a **Target Currency**.
3. Enter the amount to be converted.
4. Click **Convert** to get the exchange rate.
5. Click **Show Exchange Rate Graph** to see the top 10 exchange rates for the base currency.

## API Used
This application uses the [ExchangeRate-API](https://www.exchangerate-api.com/) for fetching live exchange rates.

## Screenshot
![Currency Converter UI](https://via.placeholder.com/500x300.png?text=Currency+Converter+UI)

## Contributing
Feel free to fork the repository and submit pull requests with improvements or additional features.

## License
This project is licensed under the MIT License.

