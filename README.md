# Redline Exchange

Redline Exchange is a responsive, real-time currency converter powered by the Frankfurter API. It pairs practical exchange-rate calculations with a premium red-and-black interface and a signature wallet animation that visually deposits, transforms, and reveals converted money.

## Features

- Latest exchange rates for every active currency returned by Frankfurter
- Source and target currency selectors with automatic currency symbols
- Animated wallet deposit, conversion, count-up, and particle-burst sequence
- Clear loading, validation, success, and API error states
- Currency swapping and same-currency conversion support
- Responsive desktop, tablet, and mobile layouts
- Reduced-motion support for accessibility
- No API key or secret configuration required

## Run locally

This is a static HTML, CSS, and JavaScript project, so there are no packages to install.

1. Clone the repository:

   ```bash
   git clone https://github.com/david555787/currency_converter.git
   cd currency_converter
   ```

2. Start a local web server from the project root:

   ```bash
   python3 -m http.server 4173 --directory dist
   ```

3. Open [http://localhost:4173](http://localhost:4173) in your browser.

An internet connection is required while using the converter because rates and the supported currency list are loaded from Frankfurter.

## Tech stack

- Semantic HTML5
- Modern CSS with responsive layouts and keyframe animation
- Vanilla JavaScript and the Web Animations API
- `Intl.NumberFormat` for localized currency display
- Frankfurter REST API v2

## Exchange-rate data

Exchange-rate and currency data comes from [Frankfurter](https://frankfurter.dev/), a free, keyless REST API backed by central banks and official sources. This project uses the current currency list and single-pair rate endpoints; it is intended for reference conversion rather than high-frequency trading.

## Project structure

```text
dist/
├── index.html          # Application markup
├── styles.css          # Theme, responsive layout, and animation
├── app.js              # API integration and conversion behavior
└── redline-wallet.png  # Wallet centerpiece artwork
```
