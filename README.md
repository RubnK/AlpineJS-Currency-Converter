# AlpineJS Currency Converter using ExchangeRate-API

**Author: [@RubnK](https://github.com/RubnK)**

This Alpine.JS app is a currency converter that utilizes the ExchangeRate-API to provide accurate and up-to-date currency exchange rates. It allows users to convert between different currencies using current market rates and save preferred currencies for quick access.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Configuration](#configuration)
- [Features](#features)
- [Screenshots](#screenshots)
- [Contributing](#contributing)

## Prerequisites
To use this app, you will need:
- An API key from [ExchangeRate-API](https://www.exchangerate-api.com/) - Sign up to obtain an API key.
- Basic understanding of Alpine.JS and JavaScript.

## Setup
1. Clone or download this repository to your local machine.
2. Obtain an API key from [ExchangeRate-API](https://www.exchangerate-api.com/).
3. Insert your API key in the `apiKey` variable in the JavaScript part of the app.
4. Open the `index.html` file in your browser and you’re good to go!

## Configuration
To configure the API key, locate the following line in the JavaScript section of your `index.html` file:

```javascript
apiKey: 'YOUR_API_KEY', // Replace 'YOUR_API_KEY' with your actual ExchangeRate-API key
```

## Features
- Convert amounts between different currencies using real-time exchange rates.
- Add change fees (in percentage) to the conversion.
- Save your favorite currencies for quick access.
- Easily remove saved currencies from the list.
- Automatically updates conversions when currencies or fees are modified.

## Screenshots
![convertisseur_devises](https://github.com/user-attachments/assets/134b62cd-88a1-41bf-acc2-5186f4e6423c)

## Contributing
Feel free to contribute to the project by submitting issues or pull requests.
