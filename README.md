# Cryptoverse

Cryptoverse is a web application built with React.js that provides users with comprehensive information about various cryptocurrencies. It leverages multiple APIs to deliver real-time data on cryptocurrency prices, market trends, historical data, and more.

## Table of Contents 📚

- [Introduction](#introduction)
- [Features](#features)
- [Screenshot](#screenshot)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction🚀

Cryptoverse is a user-friendly application designed for cryptocurrency enthusiasts, traders, and investors. It provides real-time data on cryptocurrency prices, market trends, and historical data, allowing users to stay informed and make educated decisions.

## Features🛠️

- **Real-Time Cryptocurrency Prices**: Get up-to-date prices of various cryptocurrencies.
- **Market Trends**: View current market trends and analysis.
- **Historical Data**: Access historical data for in-depth analysis.
- **Responsive Design**: Accessible on various devices, including desktops and mobiles.
- **User-Friendly Interface**: Intuitive and easy-to-use interface.
- **Watchlist**: Create a personalized watchlist for your favorite cryptocurrencies.

## Screenshot📷

![Cryptoverse_1](https://github.com/BoddepallyVenkatesh06/Cryptoverse/blob/main/Screenshot_1.png)
![Cryptoverse_2](https://github.com/BoddepallyVenkatesh06/Cryptoverse/blob/main/Screenshot_2.png)

## Technologies Used🖥️

- **Frontend**: React.js, Redux, Bootstrap
- **APIs**: CoinGecko API, CryptoCompare API
- **Deployment**: Vercel

## Getting Started🎯

### Prerequisites📋

Before you begin, ensure you have the following installed on your system:
- Node.js
- npm (Node Package Manager)

### Installation⚙️

1. Clone the repository:

```bash
git clone https://github.com/BoddepallyVenkatesh06/Cryptoverse.git
cd cryptoverse
```

2. Install dependencies:

```bash
npm install
```

3. Get API keys from [CoinGecko](https://www.coingecko.com/en/api) and [CryptoCompare](https://min-api.cryptocompare.com/documentation).

4. Create a `.env` file in the root directory and add your API keys:

```
REACT_APP_COINGECKO_API_KEY=your_coingecko_api_key
REACT_APP_CRYPTOCOMPARE_API_KEY=your_cryptocompare_api_key
```

## Usage📈

To start the development server, run:

```bash
npm start
```

This will start the application in development mode at `http://localhost:3000`.

To build the application for production, run:

```bash
npm run build
```

This will create a production-ready build in the `build` directory.

## Contributing❤️

Contributions are welcome! If you'd like to contribute to Cryptoverse, please follow these steps:

1. Fork the project.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License📝

```
MIT License

© 2024 Venky Kumar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
