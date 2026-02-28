# Store Wizard

<p align="center">
  <img width="300" height="300" alt="Store Wizard Icon" src="https://github.com/user-attachments/assets/c84fbfbe-2fc3-473c-9eaa-afc7bc2588c9" />
</p>

A macOS utility that helps developers price their App Store subscriptions fairly across different countries using Purchasing Power Parity (PPP).

<img width="963" height="639" alt="Screenshot 2026-02-14 at 21 56 24" src="https://github.com/user-attachments/assets/304d28c0-d34e-413f-9785-e346215378b0" />

## 🚀 What it does

Pricing your app globally is hard. A $10 subscription might be affordable in the US, but prohibitively expensive in other countries. **Subscription Price Index** solves this by calculating the equivalent price in each territory based on economic indices.

It connects directly to App Store Connect to fetch your apps and current pricing, then suggests optimized prices for each region.

## ✨ Features

-   **PPP Pricing Engines**: Calculate prices using:
    -   🍔 **Big Mac Index**: Based on the price of a Big Mac in different countries.
    -   🎬 **Netflix Index**: Based on standard Netflix subscription costs.
-   **App Store Connect Integration**:
    -   Fetches your Apps, Subscription Groups, and Subscriptions.
    -   Displays current pricing details.
-   **Secure**: All API keys are stored securely in the macOS Keychain. They never leave your device.
-   **Auto-Updates**: Automatically checks for the latest version on launch.

## 🛠 Usage

1.  **Configure API Keys**: Launch the app and go to **Settings**. Add your App Store Connect API Key (p8 file), Key ID, and Issuer ID.
2.  **Select App**: Your apps will load in the sidebar. Select one to view its details.
3.  **View Subscriptions**: Browse your subscription groups and individual products.
4.  **Analyze Prices**: Select a subscription to see price suggestions for different territories based on your chosen index.

## 🔒 Security Note

This app runs locally on your machine. Your App Store Connect API keys are stored in the system Keychain and are only used to verify your identity with Apple's servers.

## 📦 Installation

Download the latest release from the [Releases Page](../../releases).

## ☕ Support Store Wizard

If you find Store Wizard helpful and want to support its development, feel free to buy me a coffee!

<a href="https://www.buymeacoffee.com/marcelolaprea" target="_blank">
<img alt="qr-code" src="https://github.com/user-attachments/assets/d38894a7-0d3b-4d50-a4e6-c9a8eb88664d" style="height: 217px !important;width: 217px !important;"/>
</a>

---
Created by [Marcelo Laprea](https://github.com/lapreamarcelo)  
X: [https://x.com/marcelojose_dev](https://x.com/marcelojose_dev)

