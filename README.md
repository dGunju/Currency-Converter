# Currency converter

## A currency converter with multi-converter/exchange rate support on a single page.

Web App: https://650b1c27752dff0cd9bc06a2--adorable-swan-284403.netlify.app/

This is a web application written in React allowing user to get exchange rates and convert currencies based on user's input amount, along with the functionality to add multiple converters to the same page to make the conversion more convenient instead of switching between multiple tabs.

## What we implemented

- Custom dropdown select component: search input, keyboard accessibility
- Convert a given amount from base currency to target currency and vice versa
- Custom hook to store recent fetched exchange rates in sessionStorage
- The add button to add more currency converters

## Tools used

- React, Vite
- Exchange rate API: [Fixer](https://apilayer.com/marketplace/fixer)
- Icons (svg): [Material Icons](https://mui.com/material-ui/material-icons/)

## Repository

```BASH
https://github.com/Ad3b1y1/Currency-Converter.git
```

## Installation

```BASH
git clone https://github.com/Ad3b1y1/Currency-Converter.git
```

Create A Vite Project
```BASH
npx create-vite Currency-Converter --template react
``

Navigate the project directory

```BASH
cd Currency-Converter
```

## Install dependencies

```BASH
npm install
```

Get an API key from Fixer API

You can get a free API key from [Fixer official website](https://fixer.io/) or through [APILayer](https://apilayer.com/marketplace/fixer-api). Once you have your API key, place the API URL and API key in a .env file.

Run the app in development mode

```BASH
npm run dev
```

## Authors

Jonathan Adegunju (jonathanadegunju@gmail.com)
Opeoluwa Adeyemi (opeoluwaadebiyi@outlook.com)