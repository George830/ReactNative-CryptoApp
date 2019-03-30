# React Native Crypto App

### Using Public API from coinmarketcap to render a list of cryptocurrencies with its prices.


## Instruction to run
```bash
cd crypto_react_native_app
npm install
react-native run-ios (For IOS)
react-native run-andriod (For Android)
```

## Trouble Shooting
- Bundling Error : `react-native start --reset-cache`

## Working Features
- Home Screen : Fetches and renders a list of cryptocurrencies from **API**
- Favourite Screen : Fetches and renders a list of cryptocurrencies from **AsyncStorage**
- Shake the phone to navigate to *Favourites* or *Home* screen
- Add/removes cryptocurrency to Favourite List using the AsyncStorage
- Search by the name of cryptocurrency


## Components
- CryptoList : Lists all cryptos from **API**
- FavCryptoList : Lists of all cryptos in Favourite List from **AsyncStorage**
- CryptoItem : Shows the detailed view of cryptocurrency such as *Prices*, *Price Changes*, add or remove from Favourite list
